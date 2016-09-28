# Web-Mining-Project

Prediction_of_Users_Web_Browsing_Behaviour

Web Mining Project Title: Prediction of User’s Web-Browsing Behavior Using All-Kth Markov Model.

Introduction:

Web prediction is a classification problem in which we attempt to predict the next set of Web pages that a user may visit based on the knowledge of the previously visited pages. Such knowledge of user’s history of navigation within a period of time is referred to as a session. These sessions, which provide the source of data for training, are extracted from the logs of the Web servers, and they contain sequences of pages that users have visited along with the visit date and duration. The Web prediction problem (WPP) can be generalized and applied in many essential industrial applications such as search engines, caching systems, recommendation systems, and wireless applications. Therefore, it is crucial to look for scalable and practical solutions that improve both training and prediction processes. Improving the prediction process can reduce the user’s access times while browsing, and it can ease network traffic by avoiding visiting unnecessary pages.

Description:

In this work, we analyze and study Markov model and All-Kth Markov model in Web prediction. We propose FP-tree technique to find the frequent patterns and these patterns are used as input to the All-Kth Markov model for web prediction. In many applications, first-order Markov models are not very accurate in predicting the user’s browsing behaviour, since these models do not look far into the past to correctly discriminate the different observed patterns. As a result, higher-order models are often used. Unfortunately, these higher-order models have a number of limitations associated with high state-space complexity, reduced coverage, and sometimes even worse prediction accuracy. One simple method to overcome some of these problems is to train varying order Markov models and use all of them during the prediction phase, as is done in the All-Kth Order Markov model. The code is written in JAVA and we have used MySQL as database to store and collect data. We have used standard benchmark data sets to analyze, compare, and demonstrate the effectiveness of our techniques. Our experiments on a variety of data sets have shown that the proposed technique consistently outperform the single-order Markov models, both in term of state complexity as well as improved prediction accuracy.

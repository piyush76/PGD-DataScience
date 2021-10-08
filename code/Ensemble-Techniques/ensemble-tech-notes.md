How many types of ensemble techniques ? 
- Bagging and Boosting


- Ensemble Technique is all about you pick multiple models and combine them to get the right pridections. We create n different models and each one of them are different than each other. 
- We believe than having multiple models for predections is better than have one. 
- The whole idea is by combining the models which have accuracy of 90% we can get the right predictions. 
- Models should be independent of one another. 
- Ensemble techniques can be used for both Regression as well as classification.  

What is Bagging ? 
-- is a bootstraping aggregation.
-- Sample data with replacement. 
-- in bagging we create models from a different subset of data from original dataset. 
-- The models are independent of each other. 
-- Bagging is a parallel process.
-- Equal weightage to each weak learner. 
-- Samples are independent of each others. 


what is Random forest ? 
-- An ensemble of decision trees is a Random forest. 
-- Random forest make it easy to build uncorrelated learners.
-- Collection of the decision trees.
-- We also choose not just the rows of sample data but also choose the features or column to build the model. 



What is Boosting ? 

 -- In boosting we take a dataset -- > Create a Model - Then create a dataset from the model --> Create a model and similierly. 
 -- This is a Sequential process. 
 -- Boosting is considered very expensive as this use a lot of resources.
 -- Each model learns from previous models error or mistakes. 
 -- Addition of a learner boost the accuracy of the model.  
 
 
Boosting Methods. 
-- Adaptive Boosting: 
       -- Each model pays more attention to the previous model, so that subsequent model can be built in a way to help previous learner or model.     


-- Gradiant boosting. 
    -- Each model in sequence fits on residual errors of the previous model.  
    -- 
    
XGBoost
 -- XGBoost is 

       










# Forecasting-Firm-Collapse-SAS-Enterprise-Miner

**Introduction**

This project focuses on predicting a firm's potential financial distress: aiming to forecast firm collapse / bankruptcy through sophisticated predictive modeling using SAS Enterprise Miner. Utilizing the SEMMA framework (Sample, Explore, Modify, Model, Assess), we've developed robust models that integrate various econometric measures to provide precise forecasts of a firm's financial condition.

**Objective**

To predict firm collapse / bankruptcy using advanced predictive analytics, thereby aiding stakeholders in preemptive decision-making to mitigate risks associated with firm collapse.

**Dataset Description**

The datasets contain following files:
- bankruptcy_Train.csv - the training set with 64 predictors and 1 target variable
- bankruptcy_Test_X.csv - the test set with ID and 64 predictors
- bankruptcy_sample_submission.csv - the sample submission with ID and the predicted probability of firm bankruptcy

**Methodology**

Following the SEMMA framework, our methodology encompasses:
1. **Sampling**: Initial data sampling and transformation.
2. **Exploration**: Examining patterns, trends, and variable importance.
3. **Modification**: Data preparation for modeling.
4. **Modeling**: Application of Neural Network, Gradient Boosting, and Ensemble models.
5. **Assessment**: Model evaluation based on AUC and Misclassification metrics.

**Model and Results**

After exploring a variety of models, Our final model is a combination of **Neural Network**, **Gradient Boosting** and **Ensemble** models, achieved a prediction accuracy of **96.197%**.

![image](https://github.com/AravindTeja35/Forecasting-Firm-Collapse-SAS-Enterprise-Miner/assets/163460197/fc3105f9-8898-48b1-9148-729c8a700b85)


**Tuning Parameters**

The strategic integration of models and the fine-tuning of parameters led to a significant enhancement in prediction accuracy:
- Gradient Boosting: Iterations = 80. Shrinkage = 0.08. Depth = 8.
- Neural Network: Iterations = 167 (iterations having less missclassification rate is considered)
- Ensemble: Combination technique = Voting.


**Kaggle Competition**

Our team 'Kanya Rasi', secured 1st rank out of 45 participating teams in Kaggle competition as part of 'Fall 2023 MGMT571 Final Project on Classification' with prediction accuracy of **95.38%** accuracy on public leaderboard and **96.197%** accuracy on private leaderboard.
Competition link: https://www.kaggle.com/competitions/fall-2023-mgmt571-final-project-on-classification/leaderboard

**Conclusion**

Our project underscores the potency of integrating diverse predictive models to forecast firm collapse with high accuracy. The synergy between Neural Networks, Gradient Boosting, and Ensemble techniques, each meticulously fine-tuned, demonstrates the importance of model selection and parameter optimization in predictive analytics. This approach not only achieved remarkable prediction accuracy but also enriched our understanding of predictive modeling's nuances, highlighting the value of methodical experimentation and assessment in tackling complex financial forecasting challenges.

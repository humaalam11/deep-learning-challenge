# deep-learning-challenge

Objective: Help the nonprofit foundation Alphabet Soup with a machine learning-neural network model that will help them predict which applicant to fund that will have the best chance of success in their ventures. We have a CSV file with these fields. 

![image](https://github.com/humaalam11/deep-learning-challenge/assets/130116747/5ef303bf-a785-4aa9-843f-78bea4c3cbb0)

**We will be training:**

**y** = IS_SUCCESSFUL

**X** = EIN, NAME, APPLICATION_TYPE, AFFLIATION, CLASSIFICATION, USE_CASE,
    ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATION, ASK_AMT

**Getting Started:**

1) Dropping Non-Beneficial Columns: EIN and NAME
2) Checking unique values of each remaining column
3) Creating value count bins for APPLICATION_TYPE and CLASSIFICATION column to have a condensed dataset to train the model
4) Convert categorical data to numeric data with "pd.get_dummies" to help with model training

**Training the Model:**
1) Using deep neural learning, we have created layers:

![image](https://github.com/humaalam11/deep-learning-challenge/assets/130116747/7fb3c2da-3866-4b48-9b64-089e6581d43b)

2) Compile and Train the model

![image](https://github.com/humaalam11/deep-learning-challenge/assets/130116747/80855cac-f4f9-4db6-a7cb-68b13b047b1a)

3) Tested the model and saved the model

   ![image](https://github.com/humaalam11/deep-learning-challenge/assets/130116747/89ba356a-ac90-4412-b378-4b63543cf580)



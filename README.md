# Project 2 - Ames Housing Data and Kaggle Challenge

Welcome to the Housing Prediction Project! Let's model!

**Primary Task:**

You are tasked with creating a machine learning model based on the Ames Housing Dataset. This model will predict the price of a property at sale. The Ames Housing Dataset is contains over 70 columns of different features relating to houses.

---
## Project Files
This project used 2 provided datasets:
1. [Training Dataset](https://github.com/larafares/AmesHousingAnalysis/blob/main/datasets/train.csv)
2. [Test Dataset](https://github.com/larafares/AmesHousingAnalysis/blob/main/datasets/test.csv)

Initially, I assumed the best predictions would come from a simple model using features that are highly correlated with the Sale Price. However, I quickly learned that almost every variable played a small role in the determining the Sale Price.

Although this problem was intended for a [Kaggle Competition](https://www.kaggle.com/c/dsir-907-project-2/), it ultimately served as a challenge for myself to rethink how I understood approached and understood data. This project also helped me appreciate pipelines and column transformers more; since there were many models trained for this project, it made working with categorical and numeric data much easier.

## Next Steps
1) Look into feature engineering, like  the house age, renovation age, or looking into the house condition / quality
2) Making an ensemble model
3) Taking a deeper dive on what causes the model to underestimate the value of a house

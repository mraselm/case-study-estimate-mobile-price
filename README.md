# Estimating Mobile Phone Price Ranges using Machine Learning

This project predicts the price range of mobile phones using machine learning models. Based on key technical specifications like battery, RAM, camera, connectivity, and screen size, the model classifies phones into four price categories: Low, Medium, High, and Very High.

![Case Study Overview](Case%20Study%20-%20Estimating%20Price%20Range%20using%20Machine%20Learning.png)

## Dataset
- 2000 samples, 21 features
- Target: `price_range` (0=Low, 1=Medium, 2=High, 3=Very High)

## Tools & Techniques
- R Programming
- Data preprocessing & feature engineering
- SVM (tuned), Random Forest

## Files Included
- `train.csv`: Training dataset
- `test.csv`: Testing dataset
- `Mobile_Case.R`: R script for model building
- `svm_tuned_model.rds`: Final tuned SVM model
- `Case Study - Estimating Price Range using Machine Learning.png`: Problem statement

## Outcome
Provides accurate price range classification and identifies key features affecting mobile phone pricing.

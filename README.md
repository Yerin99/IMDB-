# IMDB Movie Review Sentiment Analysis

This project analyzes the sentiment of IMDB movie reviews using machine learning models. The goal is to classify reviews as positive or negative and extract meaningful insights using Logistic Regression and other models.

## Project Overview
- Dataset: IMDB Movie Reviews (50,000 reviews)
- Goal: Sentiment classification and feature analysis.
- Models: Logistic Regression, Random Forest, Naive Bayes.

## Key Results
| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 89.7%    |
| Random Forest        | 85.3%    |
| Naive Bayes          | 85.8%    |

## Why Logistic Regression?
- Provides **interpretable** feature importance.
- **Performs well** with sparse, high-dimensional text data.

## Experiments
### Feature Analysis
- Top positive words: `great`, `excellent`, `amazing`, `perfect`
- Top negative words: `worst`, `awful`, `boring`, `terrible`

### Word Cloud
![positive words wordCloud](https://github.com/user-attachments/assets/53ddd985-6d40-40f6-9ccb-dadc1304fc3b)
![negative words wordCloud](https://github.com/user-attachments/assets/7a2c4ae0-78eb-4e4b-a616-773afa032aba)

### Central Limit Theorem
I conducted CLT experiments on review length, negation count, and exclamation marks to validate statistical properties.
![CLT on Length of Reviews](https://github.com/user-attachments/assets/3985e6bb-928d-4677-9afb-0878e753be64)
![CLT on Negation Count in Reviews](https://github.com/user-attachments/assets/9c94a46d-8aaa-4513-8b22-36854410c1b3)
![CLT on Exclamation Mark Count in Reviews](https://github.com/user-attachments/assets/fe6f144d-a2dd-4007-a47f-365b7003d2a3)

## How to Run
Just download the ipynb file, and run it!

## Contact
For questions or suggestions, please reach out to [diluny2@naver.com](diluny2@naver.com)!

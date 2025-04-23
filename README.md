# 🏡 Fine-Tuning BERT for Property Type Classification

## 📌 Project Summary
This project fine-tunes a pre-trained BERT model (`bert-base-uncased`) to classify real estate listings based on textual descriptions into categories like `single_family`, `condo`, `mobile`, etc.

## 🧠 Key Features
- Real estate data from Utah (2024)
- 13 unique property types
- Preprocessing, label encoding, BERT tokenization
- Fine-tuning on 1000 listings with validation/test split
- Learning rate tuning
- Final inference function + saved model

## 📊 Results
- **Validation Accuracy**: 87.0%
- **Test Accuracy**: 86.0%
- **Test F1 Score (macro)**: 0.3781

## 🛠️ How to Run
1. Upload notebook to Google Colab
2. Upload `real_estate_utah.csv` or fetch via Kaggle
3. Run all cells sequentially
4. To test inference:
```python
predict_property_type("Charming 3BHK townhouse with open plan and community amenities.")




# 💇‍♀️ Hairstyle Classification

![Hairstyle Image](https://howng.com/wp-content/uploads/2016/10/traditional-hairstyles-e1477039899416.jpg)

This project focuses on the classification of hairstyles using image data sourced from Instagram. The dataset includes **10,000 images** that have been automatically grouped into hairstyle clusters using a visual recognition algorithm. Each image is accompanied by social engagement metadata and time-based posting information.

👉 For more machine learning projects, visit the main repository:  
🔗 [Machine Learning Projects by @erdiolmezogullari](https://github.com/erdiolmezogullari/ml-projects)

---

## 📦 Dataset Description

Each entry in the dataset includes:

- **`id`**: Unique identifier for the Instagram post  
- **`user_id`**: Unique identifier for the Instagram account  
- **`url`**: Link to the image post  
- **`likes`**: Number of likes received  
- **`comments`**: Number of comments  
- **`cluster`**: Hairstyle cluster label assigned by the model  
- **`influencer_flag`**: Binary label (1 if likes > 500; 0 otherwise) identifying influencer posts

---

## 🗓️ Date Features

The dataset includes various time-related variables to allow for trend analysis and temporal modeling:

- **`date_unix`**: UNIX timestamp of the post date  
- **`date_week`**: Week number (non-ISO format)  
- **`date_month`**: Month of the post  
- **`date_formated`**: Formatted post date (DD/MM/YY)

These can be customized or transformed depending on the goals of your analysis.

---

## 🎯 Project Objectives

- Classify images based on hairstyle clusters  
- Analyze social engagement (likes, comments) per cluster  
- Identify influencer patterns based on engagement metrics  
- Explore trends over time using date-based features

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, OpenCV
- Jupyter Notebooks
- Matplotlib / Seaborn for visualization

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Ankitkumar1141/Machine-Learning-Projects.git
   cd hairstyle-classification
2. Setup the virtual environment:
    python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install all requirements
   pip install -r requirements.txt




## 📊 Potential Analyses
Correlation between hairstyle types and engagement

Temporal posting patterns of influencers

Feature extraction from images for training classifiers

## 📄 License
This project is open-source and available under the MIT License. See the LICENSE file for more information.


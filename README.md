# Email Spam Detection using Machine Learning

## Project Objective
The objective of this project is to build a machine learning model that can classify messages as spam or non-spam (ham). Spam detection is an important application of natural language processing that helps protect users from fraudulent and unwanted messages.

---

## Dataset

## Dataset Name
SMS Spam Collection Dataset

## Dataset Source
UCI Machine Learning Repository (via GitHub)

## Dataset Download Link
https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv

## Dataset Description
The dataset contains 5,574 SMS/email messages with two columns:
- label: spam or ham
- message: text content of the message

---

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook / Google Colab

---

## Methodology
1. Downloaded and loaded the dataset.
2. Performed basic data exploration.
3. Converted text labels into numeric format.
4. Transformed text data using Count Vectorization.
5. Split data into training and testing sets.
6. Trained a Naive Bayes classifier.
7. Evaluated the model using accuracy, confusion matrix, and classification report.
8. Visualized results using a confusion matrix heatmap.

---

## How to Run the Project
1. Download the dataset using the provided link.
2. Save the file as `spam.csv`.
3. Place the dataset in the same directory as the notebook.
4. Open `Email_Spam_Detection.ipynb`.
5. Run all cells to view results.

---

## Expected Output
- Dataset preview and structure.
- Accuracy score of approximately 97–99%.
- Classification report showing model performance.
- Confusion matrix visualization.

---

## Results and Conclusion
The Naive Bayes classifier performs exceptionally well in detecting spam messages.  
This project demonstrates the effectiveness of machine learning and natural language processing techniques in solving real-world classification problems.

---
## Author
Shivanjali Kadam


# Project Title  
Spam Detection with Multinomial Naive Bayes  

## Project Overview  
This project aims to classify emails as **spam** or **not spam** using the Spambase dataset. The classification is performed using the **Multinomial Naive Bayes algorithm**, which works well with text-based data such as word counts or frequencies. The model helps identify spam emails accurately and efficiently, making it useful for filtering unwanted messages.

## Dataset  
- **Dataset Name:** spambase.data  
- **Source:** Available from UCI's machine learning repository.  
- **File Format:** CSV  
- **Target Column:** Binary label (0 = Not Spam, 1 = Spam)

## Libraries Used  
- **pandas:** For data loading and manipulation.  
- **scikit-learn:** For model building and evaluation.  
- **matplotlib** and **seaborn:** For data visualization.  

## How to Run the Code  

### Step 1: Clone or Download the Repository  
- Download the project files or clone the repository to your local machine.  

### Step 2: Place the Dataset  
- Ensure that the `spambase.data` file is placed in the correct path as referenced in the script.

### Step 3: Install Dependencies  
Run the following command to install all required libraries:  

### Step 4: Execute the Python Script  
- Run the provided Python script to train and evaluate the spam detection model. The script will:  
  - Load the dataset using pandas.  
  - Preprocess the data by scaling features with MinMaxScaler.  
  - Train a **Multinomial Naive Bayes** model on 80% of the data.  
  - Evaluate the model using metrics like **accuracy, classification report, and confusion matrix**.  
  - Visualize the confusion matrix using seaborn.

### Step 5: View the Results  
- After running the code, the script will display the model’s **accuracy** and **classification report**.  
- A heatmap visualization of the confusion matrix will also be shown to provide insight into classification performance.  

## How the Dataset Was Used  

1. **Data Preprocessing:**  
   - The features were separated from the target column (spam/not spam).  
   - **MinMaxScaler** was used to normalize feature values between 0 and 1.  
   - The dataset was split into **80% training** and **20% testing** sets.  

2. **Model Training and Evaluation:**  
   - The **Multinomial Naive Bayes algorithm** was chosen because it handles frequency-based features effectively.  
   - The model achieved **87.19% accuracy** on the test set, showing good performance.  
   - A **classification report** was generated to display precision, recall, and F1-score.  
   - The **confusion matrix** was used to visualize the number of correct and incorrect predictions.  

3. **Analysis Goal:**  
   - The goal of the project is to accurately classify emails and filter spam messages.  
   - The insights from the classification metrics can help in identifying areas where the model might need improvements.  
   - This project demonstrates the efficiency of **Multinomial Naive Bayes** in solving spam detection problems.


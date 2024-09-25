## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![Screenshot 2024-09-25 101242](https://github.com/user-attachments/assets/925e0bc7-3383-4d33-8077-ea295a9f07d7)

![Screenshot 2024-09-25 101256](https://github.com/user-attachments/assets/e83e05c4-27b7-4beb-82d9-bd34ea27517c)
![Screenshot 2024-09-25 101309](https://github.com/user-attachments/assets/df6b2701-eaa0-47fd-bf05-0749ff9c94e8)
![Screenshot 2024-09-25 101338](https://github.com/user-attachments/assets/d848615f-4d21-4b8e-9fb4-a9341ab7c1a1)


# RESULT:
      Thus, performing Feature Encoding and Transformation process for the given data set is completed.

       

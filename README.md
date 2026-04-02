# Problem Overview

## Goal
The goal of this problem is to predict whether a passenger was **satisfied** or **not satisfied** based on their overall experience traveling on the **Shinkansen Bullet Train**.

---

## Dataset

The problem consists of two separate datasets:

- **Travel Data**: Contains information about passengers and attributes related to the Shinkansen train on which they traveled.
- **Survey Data**: Contains aggregated survey results reflecting post-service experience.

Both datasets should be treated as **raw data**, and you are expected to perform necessary **data cleaning and validation** steps.

The data is split into two groups:

- `Train_Data`
- `Test_Data`

---

## Target Variable

- **Overall_Experience**
  - `1` → Satisfied  
  - `0` → Not Satisfied  

The **training set** includes labels for the target variable and should be used to build your machine learning model.

The **test set** does not include labels. You are required to predict the `Overall_Experience` for each participant.

---

## Data Dictionary

All variables are self-explanatory.  
Survey levels and additional details are provided in the **Data Dictionary file**.

---

## Submission File Format

You must submit a CSV file with:

- **35,602 rows** (plus header)
- **Exactly 2 columns**:
  - ID
  - Overall_Experience
 
- `Overall_Experience` must contain:
  - `1` → Satisfied  
  - `0` → Not Satisfied  

---

## Evaluation Criteria

### Accuracy Score

The evaluation metric is **accuracy**, defined as:

\[
\text{Accuracy} = \frac{\text{True Positives} + \text{True Negatives}}{\text{Total Observations}}
\]

- Best possible score: **1.0 (100%)**
- Worst possible score: **0.0 (0%)**

# KNN Classification - Housing Price Categorization

This project demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm to classify houses into categories based on their features using the Scikit-learn library.

## Objective
To classify houses as **Expensive (1)** or **Not Expensive (0)** based on various attributes like area, number of bedrooms, location features, and furnishing status.

## Dataset Features
- **Price**: Target column used to define expensive or not.
- **Area**: Total square footage of the house.
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of bathrooms.
- **Stories**: Number of stories.
- **Mainroad**: Whether the house is on the main road (Yes/No).
- **Guestroom**: Guest room availability (Yes/No).
- **Basement**: Basement availability (Yes/No).
- **Hot water heating**: Availability of hot water heating (Yes/No).
- **Airconditioning**: Presence of air conditioning (Yes/No).
- **Parking**: Number of parking spots.
- **Prefarea**: Whether the house is in a preferred area (Yes/No).
- **Furnishing status**: Furnishing status (Fully Furnished, Semi-Furnished, Unfurnished)

## Steps Performed
1. **Data Preprocessing**:
   - Label Encoding of categorical variables.
   - Binarization of target variable using median price.

2. **Model Building**:
   - Train-test split.
   - Standard scaling of features.
   - Training KNN with `k=5`.

3. **Evaluation**:
   - Confusion matrix.
   - Classification report.
   - Accuracy score.

4. **Visualization**:
   - Confusion matrix heatmap.
   - Error rate vs. different `k` values plot.

## Results
- **Model Accuracy**: ~65%
- Classification report shows balanced performance across both classes.

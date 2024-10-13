# Linear Regression on Housing Data

This notebook contains a linear regression analysis on a housing dataset. The dataset includes various features of houses such as area, price, number of bedrooms, and more. The goal of the analysis is to understand the relationship between the features and the price of houses.

## Dataset Overview

The dataset contains 545 entries with 13 columns. The columns provide information on different attributes of the houses.

### Features:

- `price`: The price of the house (integer).
- `area`: The area of the house in square feet (integer).
- `bedrooms`: The number of bedrooms (integer).
- `bathrooms`: The number of bathrooms (integer).
- `stories`: The number of stories (integer).
- `mainroad`: Whether the house is on the main road (`yes` or `no`).
- `guestroom`: Whether the house has a guestroom (`yes` or `no`).
- `basement`: Whether the house has a basement (`yes` or `no`).
- `hotwaterheating`: Whether the house has hot water heating (`yes` or `no`).
- `airconditioning`: Whether the house has air conditioning (`yes` or `no`).
- `parking`: The number of parking spaces (integer).
- `prefarea`: Whether the house is in a preferred area (`yes` or `no`).
- `furnishingstatus`: The furnishing status of the house (`furnished`, `semi-furnished`, `unfurnished`).

## Notebook Structure

1. **Data Preprocessing**:
   - Handling missing values .
   - Encoding categorical features (e.g., converting `yes`/`no` to binary or numeric values).
   - Feature scaling or normalization .

2. **Modeling**:
   - Splitting the dataset into training and testing sets.
   - Building a linear regression model.
   - Evaluating the model's performance using metrics such as R² score, Mean Squared Error (MSE), etc.

3. **Results and Conclusion**:
   - Discussion of the model's performance.
   - Insights drawn from the analysis.

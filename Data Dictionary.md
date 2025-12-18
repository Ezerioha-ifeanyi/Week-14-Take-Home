# Week 14 - Datasets Dictionary

This folder contains all the synthetic datasets required for completing the Week 14 assignments on Data Pre-Processing and Regression.

## Folder Structure

```
Week-14 (Data Pre-Processing & Regression-1)/
│
├── Task-Datasets/
│   ├── task1_data_with_missing.csv
│   ├── task2_categorical_data.csv
│   └── task3_scaling_data.csv
│
├── Assignment-Datasets/
│   ├── assignment1_ecommerce_data.csv
│   ├── assignment2_advertising_sales.csv
│   └── assignment3_startup_profit.csv
│
└── Assessment-Dataset/
    └── housing_price_data.csv
```


## Task Datasets

### 1. task1_data_with_missing.csv
**Purpose**: Practice handling missing data with imputation techniques

**Columns**:
- `Name` (string): Customer name
- `Age` (numeric): Customer age
- `City` (categorical): Customer city
- `Income` (numeric): Annual income
- `Product_Rating` (numeric): Product rating

**Records**: 15 rows  


### 2. task2_categorical_data.csv
**Purpose**: Practice encoding categorical variables

**Columns**:
- `CustomerID` (string): Unique customer identifier
- `City` (categorical): Mumbai, Delhi, Bangalore, Chennai
- `Product_Type` (categorical): Electronics, Clothing, Furniture
- `Age` (numeric): Customer age
- `Purchase_Amount` (numeric): Purchase amount in currency
- `Purchased` (categorical): Yes/No - **Target variable**

**Records**: 20 rows


### 3. task3_scaling_data.csv
**Purpose**: Compare data distributions before and after feature scaling

**Columns**:
- `EmployeeID` (string): Unique employee identifier
- `Age` (numeric): Employee age (23-46)
- `Annual_Salary` (numeric): Annual salary ($32,000-$108,000)
- `Years_Experience` (numeric): Years of work experience (1-23)
- `Performance_Score` (numeric): Performance score (71-95)

**Records**: 25 rows



## Assignment Datasets

### 1. assignment1_ecommerce_data.csv
**Purpose**: Complete end-to-end data preprocessing pipeline

**Columns**:
- `CustomerID` (string): Unique customer identifier
- `Gender` (categorical): Male, Female, Other
- `Age` (numeric): Customer age
- `Country` (categorical): USA, UK, Canada, Australia
- `Annual_Income` (numeric): Annual income
- `Purchase_Amount` (numeric): Purchase amount
- `Repeat_Customer` (categorical): Yes/No - **Target variable**

**Records**: 100 rows


### 2. assignment2_advertising_sales.csv
**Purpose**: Build and evaluate a simple linear regression model

**Columns**:
- `Advertising_Spend` (numeric): Marketing spend in thousands of dollars
- `Sales_Revenue` (numeric): Sales revenue in thousands of dollars - **Target variable**

**Records**: 50 rows


### 3. assignment3_startup_profit.csv
**Purpose**: Build multiple linear regression model with feature selection

**Columns**:
- `RD_Spend` (numeric): R&D spending
- `Marketing_Spend` (numeric): Marketing spending
- `Administration_Cost` (numeric): Admin costs
- `Employee_Count` (numeric): Number of employees
- `Location` (categorical): Urban, Suburban, Rural
- `Profit` (numeric): Monthly profit - **Target variable**

**Records**: 60 rows


## Assessment Dataset

### housing_price_data.csv
**Purpose**: Comprehensive real-world project demonstrating all learned concepts

**Columns**:
- `Area` (numeric): House area in square feet (1,460-3,450)
- `Bedrooms` (numeric): Number of bedrooms (2-5)
- `Bathrooms` (numeric): Number of bathrooms (1-4)
- `Age` (numeric): Age of house in years (1-19)
- `Distance_City_Center` (numeric): Distance from city center in km (1.0-11.5)
- `Nearby_Schools` (numeric): Number of nearby schools (1-7)
- `Property_Tax` (numeric): Annual property tax ($2,700-$8,200)
- `Neighborhood` (categorical): Luxury, Standard, Budget
- `Garage` (categorical): Yes, No
- `Pool` (categorical): Yes, No
- `House_Price` (numeric): House price - **Target variable** ($225k-$985k)

**Records**: 200 rows

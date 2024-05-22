# British Airline Analysis

## Project Overview

This project performs an in-depth analysis of British Airlines using customer booking data and customer reviews. The primary objectives are to classify customers based on their booking behavior and to analyze customer reviews to determine overall sentiment.

## Features

1. **Customer Classification**:
   - Uses Random Forest Regression to classify customers based on booking data.
   - Identifies patterns in customer behavior to aid in targeted marketing and personalized service.
   - Reasons for using Random Forest Regression:
     - Handles large datasets efficiently.
     - Provides high accuracy through ensemble learning.
     - Manages overfitting well by averaging multiple decision trees.

2. **Sentiment Analysis**:
   - Utilizes VADER (Valence Aware Dictionary and sEntiment Reasoner) to analyze customer reviews.
   - Classifies reviews as positive, negative, or neutral to gauge customer satisfaction.
   - VADER is chosen because:
     - It is specifically attuned to social media texts.
     - Provides high accuracy in identifying sentiment in short texts.
     - Easy to implement and interpret.

## Dataset

- **Customer Booking Data**: Includes details such as booking date, flight details, customer demographics, and purchase history.
- **Customer Reviews**: Consists of textual reviews provided by customers post-travel.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ameya0930/British-Airline-Analysis.git
   cd British-Airline-Analysis

Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your contributions are well-documented and tested.

License:

This project is licensed under the MIT License. See the LICENSE file for details

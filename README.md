# CRM RFM CLTV Prediction Analysis

## Overview

This project focuses on analyzing customer value for a retail business through advanced statistical models. By leveraging RFM (Recency, Frequency, Monetary) analysis, BG-NBD (Beta-Geometric/Negative Binomial Distribution), and the Gamma-Gamma model, we aim to understand and predict the Customer Lifetime Value (CLTV). This analysis enables businesses to make informed decisions regarding customer relationship management, marketing strategies, and resource allocation.

## Features

- **RFM Analysis**: Segments customers based on their purchase history - how recently, how often, and how much they purchased.
- **BG-NBD Model**: Predicts the probability of a customer making a purchase within a specific time frame.
- **Gamma-Gamma Model**: Estimates the expected average monetary value of customer transactions.
- **CLTV Prediction**: Integrates the BG-NBD and Gamma-Gamma models to forecast the lifetime value of customers.

## Installation

To run this project, you will need Python and the following Python libraries installed:

- datetime
- pandas
- matplotlib
- seaborn
- lifetimes

You can install these libraries using pip:

```bash
pip install datetime pandas matplotlib seaborn lifetimes

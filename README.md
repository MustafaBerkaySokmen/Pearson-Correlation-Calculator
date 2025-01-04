# Pearson Correlation Calculator

## Overview
The **Pearson Correlation Calculator** is a Python-based program designed to compute the Pearson correlation coefficient between two datasets. The program implements functions to calculate the mean, standard deviation, covariance, and Pearson correlation coefficient.

## Features
- Computes the **mean** of a dataset.
- Computes the **standard deviation** of a dataset.
- Computes the **covariance** between two datasets.
- Computes the **Pearson correlation coefficient**.
- Provides a testing interface for validating calculations.

## Installation
To run this project, ensure you have **Python 3.x** installed on your system.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/pearson-correlation.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd pearson-correlation
   ```
3. **Run the script:**
   ```bash
   python PearsonCorr.py
   ```

## Usage
1. The program contains four primary functions:
   - `calc_mean(X)`: Computes the mean of dataset `X`.
   - `calc_stdev(X)`: Computes the standard deviation of dataset `X`.
   - `calc_cov(X, Y)`: Computes the covariance between datasets `X` and `Y`.
   - `calc_pearson(X, Y)`: Computes the Pearson correlation coefficient.
2. Users can modify the datasets (`X` and `Y`) in the `main()` function to test different inputs.
3. Running the script prints the computed statistical values.

## Example Output
```
mean for X: 1.833
mean for Y: 4.133
std for X: 1.027
std for Y: 2.545
covariance: 2.153
pearson: 0.817
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.


# Calcroi
## Disclaimer
## This calculator is not to be used as the only deciding factor for your inevestsments. I am not responsible for any miscalculations, errors, or decisions made as a result of using this calculator. The editable nature of the functions in this sheet means that the formulas are able to be altered, manipulated, or removed and therefore the integrity can not and should not be your only base of comparison. Always check with a real estate professional before making any major real estate investments.


## Overview

This Financial ROI Calculator is a comprehensive tool designed to assist investors and financial analysts in evaluating the return on investment (ROI) for real estate and loan-based investments. The calculator integrates multiple financial models to offer a holistic analysis, enabling informed decision-making in complex financial scenarios.

## Key Features

- **Loan Amortization Model**
- **Return on Investment (ROI) Calculation**
- **Mortgage Yield Analysis**
- **Scenario and Sensitivity Analysis**
- **Dynamic Variable Adjustments**

## How It Works

### 1. Loan Amortization Model

The Loan Amortization Model tracks the loan balance over time, breaking down each payment into principal and interest components.

**Formulas Used**:
- **Monthly Payment (PMT)**:
  \[
  PMT = \frac{P \times r \times (1 + r)^n}{(1 + r)^n - 1}
  \]
  Where:
  - \( P \) = Principal loan amount
  - \( r \) = Monthly interest rate (annual rate / 12)
  - \( n \) = Total number of payments (loan term in years \times 12)

- **Interest Component**:
  \[
  \text{Interest Payment} = \text{Remaining Balance} \times r
  \]

- **Principal Component**:
  \[
  \text{Principal Payment} = PMT - \text{Interest Payment}
  \]

- **Remaining Balance**:
  \[
  \text{Remaining Balance} = P \times (1 + r)^n - \frac{PMT \times ((1 + r)^n - 1)}{r}
  \]

### 2. Return on Investment (ROI) Calculation

The ROI Calculation model evaluates the profitability of an investment by factoring in all costs associated with acquiring and holding the property.

**Formulas Used**:
- **Total Investment**:
  \[
  \text{Total Investment} = \text{Purchase Price} + \text{Rehab Costs} + \text{Closing Costs} - \text{Borrower Down Payment}
  \]

- **Net Profit**:
  \[
  \text{Net Profit} = \text{Total Payments Received} - \text{Total Investment}
  \]

- **ROI**:
  \[
  ROI = \frac{\text{Net Profit}}{\text{Total Investment}} \times 100\%
  \]

### 3. Mortgage Yield Analysis

The Mortgage Yield Analysis feature helps users determine whether the investment meets the required yield thresholds.

**Formulas Used**:
- **Yield Required**:
  \[
  \text{Yield Required} = \left( \frac{\text{Annual Interest Payment}}{\text{Loan Amount}} \right) \times 100\%
  \]

- **Offer Yield**:
  \[
  \text{Offer Yield} = \left( \frac{\text{Total Net Profit}}{\text{Total Investment}} \right) \times 100\%
  \]

### 4. Scenario and Sensitivity Analysis

This calculator allows users to adjust key variables and assess how these changes impact ROI, net profit, and other financial outcomes.

**Formulas Used**:
- **Adjusted ROI**:
  \[
  \text{Adjusted ROI} = \frac{\text{Adjusted Net Profit}}{\text{Adjusted Total Investment}} \times 100\%
  \]
  The "Adjusted" versions of these variables are recalculated based on user-modified inputs, such as interest rates or loan terms.

### 5. Dynamic Variable Adjustments

The calculator provides real-time results as users adjust variables like interest rates, loan terms, and down payments, allowing for a more interactive analysis.

**Formulas Used**:
- The formulas dynamically update based on the user's input, recalculating the Monthly Payment (PMT), ROI, Yield, and other key metrics as described above.

## Usage

1. **Input Loan Details**: Start by entering the loan amount, interest rate, purchase price, and other relevant financial details.
2. **Adjust Scenarios**: Use the scenario analysis feature to adjust variables and explore different financial outcomes.
3. **Review Results**: Analyze the generated reports to assess the investment's ROI, yield, and other key financial metrics.

## Conclusion

This Financial ROI Calculator is a powerful tool for any investor or financial analyst looking to deeply understand the financial mechanics behind their investments. By integrating multiple models into one comprehensive tool, it provides the insights necessary to make informed, strategic decisions.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


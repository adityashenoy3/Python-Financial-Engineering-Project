# Financial Engineering Portfolio Optimization Project

## Project Overview
This project focuses on constructing an optimized financial portfolio using various technical strategies to achieve a Sharpe ratio greater than any single instrument within the portfolio. It leverages historical price data of various securities from 12/31/1999 to 12/31/2018.

## Key Features
- Analysis of a diverse set of financial instruments.
- Application of technical strategies like Moving Average Crossover (MA), Bollinger Bands (BB), and Benchmarking (BMK).
- Optimization techniques to maximize the portfolio's Sharpe ratio.

## Data
The project utilizes close price data for the following securities:
- **Equities:** 
  - Apple (AAPL) - Technology
  - Exelon Corp (EXC) - Utility
  - General Electric (GE) - Diversified High-Tech Industrial
  - Intel (INTC) - Technology
  - Pfizer (PFE) - Pharmaceutical
  - S&P 500 ETF (SPY) - Broad Market ETF
- **Fixed Income:**
  - Fidelity Investment Grade Bond Index (FBNDX)
  - Vanguard Total Bond Market Index (VBTIX)
- **Commodities:**
  - S&P GSCI Broad Commodity Index (SPGSCI)
  - Platinum (XPT)
- **Currencies:**
  - Canadian Dollar (CAD)
  - British Pound (GBP)

## Strategies Employed
- MA Crossover Strategy (flat and short)
- Bollinger Band Strategy
- Benchmark Strategy
Each strategy was applied to enhance the portfolio's performance.

## Constraints
The project adheres to the following constraints to ensure a robust and unbiased approach:
- **MA Crossover Strategy:**
  - Uniform (fastWindow, slowWindow) parameters across all equity instruments.
  - Separate or identical (fastWindow, slowWindow) parameters for fixed income, commodities, and currencies.
- **Bollinger Band Strategy:**
  - Uniform parameters across all instruments.
  - Minimum lookbackWindow of 20 to ensure stability of the standard deviation estimate.

## Analysis
- Calculation of correlation matrices.
- Mean-Variance Optimization for optimal asset allocation.
- Monte Carlo simulation for exploring various portfolio compositions.

## Portfolio Construction
A portfolio of eight chosen strategies was created, meeting specific constraints and optimization parameters to achieve a high Sharpe ratio.

## Installation and Usage
- Ensure you have Jupyter Notebook or an equivalent environment to run `.ipynb` files.
- Clone the repository and navigate to the notebook file.

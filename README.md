# ttstc_project
# Multi-Asset Portfolio Risk Analysis: VaR, CVaR, and Stress Testing

A quantitative risk analytics project demonstrating Value-at-Risk (VaR), Conditional Value-at-Risk (CVaR), and scenario analysis across three portfolio allocations inspired by institutional asset management mandates.

## Project Overview

This project implements core portfolio risk measurement and stress-testing techniques used by institutional investment risk teams. It analyzes a multi-asset ETF portfolio across conservative, balanced, and aggressive allocations to demonstrate how risk metrics scale with asset allocation decisions.

**Key Capabilities:**
- Historical VaR and CVaR calculation at 95% and 99% confidence levels
- Multi-scenario portfolio analysis (Conservative, Balanced, Aggressive)
- Loss distribution visualization with risk threshold overlays

## Portfolio Construction

The analysis uses five liquid ETFs representing major asset classes:

| Ticker | Asset Class | Data Source |
|--------|-------------|-------------|
| SPY | U.S. Large-Cap Equity | massive |
| VT | Global Equity ex-US | massive |
| BND | Core Investment-Grade Bonds | massive |
| VNLA | Short-Duration Income | massive |
| VNQ | Listed Real Estate (REITs) | massive |

## Open with Colab(Simpler) or using requirement file below in your own environment
Use this link to open the notebook and run the cells sequentially
to obtian the correct output.

## Requirements
Please install the requirements using pip. Conda is preferable but riskfolio can only be 
installed with pip at the moment.

### Using pip
pip install -r requirements.txt



## Introduction

This project focuses on the optimization of TomMac's tomato processing operations. TomMac processes three types of tomatoes into four distinct products under various constraints (supply, production, demand, and contracts). The goal is to maximize annual profit by optimizing the company's resource management. The project includes a report, presentation, and a mathematical model implemented in code.

## Project Files

- **Group_11_Report.pdf**: Detailed analysis and findings on TomMac's current operations and future strategic decisions.
- **Group_11_Presentation.pdf**: A concise presentation of the TomMac case study, including key results and strategic recommendations.
- **TomMacPlan.txt**: Contains TomMac’s operational and strategic plans including new contract terms, production increases, and warehouse adjustments.
- **Group_11_Code.txt**: The code for the mathematical model used to simulate and optimize TomMac's operations under various constraints and scenarios.

## Features

1. **Base Case Scenario**: 
   - Annual income: £136,498
   - Annual cost: £112,006.3
   - Maximized annual profit: £24,491.7
   - Breakdown by quarters is available in the report and presentation.
   
2. **Strategic Decisions**:
   - Three key decisions: Renting a new warehouse, signing a new contract, and increasing production limits.
   - The most profitable strategy involves signing a new contract and renting additional warehouse space, resulting in an increased annual profit of £56,041.7.

3. **Mathematical Model**:
   - Implemented in Xpress-Mosel to handle quarterly constraints and optimize production and sales.
   - Decision variables include the use of tomato varieties, product sales, stock levels, and warehouse capacity.
   - The model supports scenario testing for future strategic arrangements.

## Usage

1. **Model Execution**:
   - The code is written in Xpress-Mosel (MMXPRS). 
   - To execute the model, run the `Group_11_Code.txt` in a compatible environment.
   - The model outputs CSV files with detailed breakdowns of income, cost, and product use per quarter.

2. **Strategic Decisions Simulation**:
   - The model can simulate different combinations of strategic decisions (warehouse expansion, production increase, and new contract acceptance).
   - Results are displayed for each scenario, including profit maximization and feasibility checks.

## Project Team

- Vojin Radovanovic
- Aleksa Scepanovic
- Yuhang Zheng
- Sebastian Tomass

## Conclusion

This project effectively models and optimizes TomMac’s operations by addressing key constraints in supply, production, and demand. The optimal strategy has been identified to maximize annual profit. Further expansion and new market considerations have been proposed for future analysis.

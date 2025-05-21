# ⚡ Resource Allocation Optimization

This project demonstrates how to solve a **resource allocation optimization problem** using Python and linear programming (via the `PuLP` library). The scenario focuses on allocating a limited amount of power (in megawatts) across various renewable energy plants to **maximize total revenue**.

## 📈 Problem Statement

We are given a set of renewable energy plants with:
- Maximum power generation capacities
- Revenue earned per MW of power produced

Given a fixed amount of total power (100 MW), we want to allocate power to these plants such that:
1. No plant exceeds its generation capacity.
2. Total power used does not exceed the available 100 MW.
3. Revenue is maximized.

## 🔢 Data

| Plant         | Max Capacity (MW) | Revenue per MW ($) |
|---------------|------------------:|--------------------:|
| Solar_Farm_1  | 50               | 70                 |
| Wind_Plant_1  | 60               | 90                 |
| Hydro_Plant_1 | 40               | 60                 |
| Solar_Farm_2  | 30               | 65                 |
| Wind_Plant_2  | 20               | 80                 |

- **Total Available Power**: 100 MW

## 🧠 Objective Function

Maximize:


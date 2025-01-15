# 🚗 Insurance Eligibility and Premium Calculator

## Overview
This project calculates **insurance eligibility** and **premium amounts** based on user inputs such as age, driving history, and driving course completion. It provides an interactive, user-friendly command-line interface to determine insurance eligibility and calculates the premium amount accordingly. Additionally, the program tracks a list of eligible users for further review.

## Features
- Calculates insurance premiums based on:
  - Age of the user
  - Driving history (e.g., presence of speeding tickets)
  - Driving course completion status
- Determines user eligibility for insurance coverage.
- Displays the premium amount if eligible.
- Maintains a list of eligible users.
- Allows checking eligibility for multiple users in one session.

## Eligibility and Premium Criteria
- **Age ≥ 25:**
  - No speeding ticket: Premium = $500
  - With speeding ticket: Premium = $1000
- **Age < 25:**
  - No speeding ticket:
    - Completed driving course: Premium = $1000
    - No driving course: Premium = $1500 (ineligible)
  - With speeding ticket:
    - Completed driving course: Premium = $1500
    - No driving course: Ineligible

## How to Use
### Prerequisites
- Install Python 3.x on your system.

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/harryallenp1/Proj_Insurancecalc.git
   cd insurance-calculator

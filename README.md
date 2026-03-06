# OPTIMAZATION MODEL

COMPANY NAME : CODTECH IT SOLUTION

NAME : KOLANKAR RAHUL MADAN

DOMAIN NAME : DATA SCIENCE

INTERNSHIP DURATION : 6 WEEKS

INTERN ID : CTIS5094

INTERNSHIP MENTOR : NEELA SANTOSH

Optimization Using Linear Programming with PuLP
Project Overview

This project demonstrates how to solve a business production planning problem using Optimization Techniques (Linear Programming) in Python.

The goal is to determine the optimal number of products to produce in order to maximize profit while satisfying resource constraints.

This project is implemented using Python and the PuLP optimization library and demonstrated in a Jupyter Notebook.

#Business Problem

A small manufacturing company produces three products:

 * Product A

 * Product B

 * Product C

Each product requires limited resources such as:

 * Machine hours

 * Labor hours

 * Raw material

The company wants to determine how many units of each product should be produced to achieve the maximum possible profit.

#Objective

Maximize total profit while respecting constraints like:

 * Limited machine hours

 * Limited labor hours

 * Limited raw material

 * Minimum production requirements

 * Maximum demand limits

#Technologies Used
Tool	Purpose
Python	Programming language
Jupyter Notebook	Project execution and demonstration
PuLP	Linear Programming optimization solver
Pandas	Data handling and analysis
NumPy	Numerical calculations
Matplotlib	Data visualization

#Project Structure
Optimization_Project
│
├── Optimization_with_PuLP_Production_Planning.ipynb
├── README.md
Optimization Model
Decision Variables

Number of units to produce for each product:

x_A, x_B, x_C
Objective Function

Maximize total profit:

Profit = 50*A + 40*B + 65*C
#Constraints

 * Machine hour limitations

 * Labor hour limitations

 * Raw material limitations

 * Minimum production requirements

 * Maximum demand limits

#Results

Optimal Production Plan:

Product	Units Produced
A	40
B	70
C	10

Maximum Profit Achieved:

5450
#Business Insights

From the optimization model we discovered:

 * The optimal production quantities for each product

 * Maximum achievable profit

 * Resource utilization levels

 * Bottleneck resources in production

The analysis showed that:

 * Labor hours and raw materials are fully utilized

 * These resources act as production bottlenecks

#Visualization

The project also includes graphs such as:

 * Resource Usage vs Capacity

 * Profit contribution by product

 * What-if analysis for capacity increase

These visualizations help understand resource efficiency and production strategy.

How to Run the Project
Step 1

Install required libraries:

pip install pulp pandas numpy matplotlib jupyter
Step 2

Open Jupyter Notebook:

python -m notebook
Step 3

Open the file:

Optimization_with_PuLP_Production_Planning.ipynb
Step 4

Run all cells:

Kernel → Restart & Run All
#Learning Outcomes

Through this project we learned:

 * How to apply Linear Programming in business problems

 * How to implement optimization models in Python

 * How to analyze resource constraints and profit maximization

 * How to visualize optimization results using graphs

Author

Rahul Kolankar

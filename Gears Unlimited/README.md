<h1>Model Optimization Script README </h1>
<h2>Overview</h2>

<p font-size = "bold">This script is designed to find the optimal order quantity for inventory management, specifically focusing on minimizing the total cost, which includes purchase cost, order cost, and holding cost. Utilizing the Economic Order Quantity (EOQ) model, the script calculates the optimal quantity of items to order that minimizes the total inventory cost. </p>

## Features

- \*\*Purchase Cost Calculation: Computes the total purchase cost based on the annual demand and unit cost.
- \*\*Order Cost Calculation: Determines the total order cost, considering the cost per order and the frequency of orders.
- \*\*Holding Cost Calculation: Calculates the annual holding cost based on the average inventory level, unit cost, and holding cost rate.
- \*\*Total Cost Optimization: Utilizes the EOQ formula to find the optimal order quantity that minimizes the total cost.

## Requirements

- Python 3.x
- NumPy: For numerical calculations
- Matplotlib: For plotting the cost functions and visualizing the optimization
- SymPy: For symbolic mathematics to derive and solve the optimization problem

## Installation

- Ensure you have Python installed, then install the required packages using pip:

'''bash
Copy code
pip install numpy matplotlib sympy

## Usage

To run the script, simply execute it in your Python environment:

- python model_optimization_script.py

- The script will calculate the optimal order quantity and plot the Total Cost function, highlighting the minimum cost point.

## Customization

You can customize the script for different inventory items by modifying the following parameters at the beginning of the script:

annual_demand: The annual demand for the item.
unit_cost: The cost per unit of the item.
order_cost: The fixed cost per order.
holding_cost_rate: The annual holding cost rate (as a fraction of the unit cost).

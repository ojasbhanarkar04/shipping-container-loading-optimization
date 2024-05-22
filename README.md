# Shipping Container Loading Optimization

This project aims to provide a 2D visualization solution to optimize space on box loading inside shipping containers. 
 
It is based on the following article by Samir Saci: https://towardsdatascience.com/maximize-the-loading-capacity-of-a-sea-container-to-reduce-your-shipping-costs-with-python-8cc02c9725a7

It uses Rectpack, a Python library containing a collection of algorithms to solve 2D knapsack problems, to pack boxes of different sizes in the most space-optimized manner inside the shipping container.

One of the enhancements done to Samir's code was to include providing CSV file input with the following fields: Container, Delivery Number, Box Number, BoxDims.
In a real-world scenario, an ERP database could be leveraged to fetch this data into a CSV file.
 
Another enhancement to the original code was to fix the frame of the displayed visualization which makes it less confusing to interpret.

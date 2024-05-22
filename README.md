# Shipping Container Loading Optimization

This project aims to provide a 2D visualization solution to optimize space on box loading inside shipping containers. 
 
It is based on the following article by Samir Saci: https://towardsdatascience.com/maximize-the-loading-capacity-of-a-sea-container-to-reduce-your-shipping-costs-with-python-8cc02c9725a7

It uses Rectpack, a Python library containing a collection of algorithms to solve 2D knapsack problems, for packing boxes of different sizes in the most space-optimized manner inside the shipping container.

One of the enhancements done to Samir's code was to use CSV file input over manual input. The file has the following fields: Container, Delivery Number, Box Number, BoxDims.
In a real-world scenario, an ERP database could be leveraged to fetch this data into a CSV file before further processing.

<img width="298" alt="containerinfoCSV" src="https://github.com/ojasbhanarkar04/shipping-container-loading-optimization/assets/166156913/1f280da8-4466-41cc-af73-ef8c696e0901">

<img width="265" alt="containerviz" src="https://github.com/ojasbhanarkar04/shipping-container-loading-optimization/assets/166156913/c1125b7e-4862-40cc-8752-f5fbabd335ac">
 
Another enhancement to the original code was to fix the frame of the displayed visualization which makes it less confusing to interpret.

# Indian-Start-Up-Funding-Analysis (2018-2021)
This repository contains an in-depth analysis of the Indian startup ecosystem as the analysis aim to explores various elements of Indian startups.
Got an error when applying conversion to the 'Amount($)' column for all datasets
Error: AttributeError: 'float' object has no attribute 'replace'. 
This is because some of the values in the Amount($) column are already float objects, and thus the replace method (which is a string method) cannot be applied to them.
To fix this, we ensure we  only apply string methods to values that are strings using this function: 
    if isinstance(amount, float):
        return amount
This is to check if the amount is already a float. Then proceed with rest of function
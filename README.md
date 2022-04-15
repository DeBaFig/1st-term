# Workshop #6

![w6](https://user-images.githubusercontent.com/46844031/163506196-b36d5cb5-bb7b-479f-a0e7-ab06252becfa.gif)

This program evaluates the cheapest cat food product based on a simple analysis. Data will be entered for three similar products and then displayed back to the user in a tabular table format. The data will be analyzed and displayed with additional calculated information in the form of a formatted table revealing the analysis. The program concludes with the suggested cheapest product.

First, the program will ask about the cat food pieces of information of 3  different options (it can be changed the CONST that save the number of products): 

````
Cat Food Product #1
--------------------
SKU           : 123
PRICE         : $1000
WEIGHT (LBS)  : 1500
CALORIES/SERV.: 100
````

Then, it will provide a summary and suggest the less expencive.

````
SKU         $Price    Bag-lbs     Bag-kg     Bag-g Cal/Serv Servings  $/Serv   $/Cal
------- ---------- ---------- ---------- --------- -------- -------- ------- -------
0000123    1000.00     1500.0   680.3894    680389      100  10631.1    0.09 0.00094
0001234    1500.00     3000.0  1360.7787   1360778      120  21262.2    0.07 0.00059
0012345     100.00     1000.0   453.5929    453592      100   7087.4    0.01 0.00014 ***

Final Analysis
--------------
Based on the comparison data, the PURRR-fect economical option is:
SKU:0012345 Price: $100.00

Happy shopping!
````

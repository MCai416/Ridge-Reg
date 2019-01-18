# Ridge-Regression

copy the file to your directory and then type 
import Ridge

OLS and Ridge Regression based on Hoerl and Kennard (1970) and Hoerl, Kennard, Baldwin (1975). 

First create an OLS or Ridge Type object, then use object.reg() for output on your console. 

OLS takes three arguments: y, X, nocons. 

X and y uses dataframe as input. This is easier to manage if you read from excel. And dataframes include columns, which looks nicer at regression.

After you include a constant, please set "nocons = False"

Default OLS and Ridge has no constant, please add in a column of constant in your dataframe. 

To use ridge, please use getK first, this is a function to retrieve the best bias/Minimum MSE estimated K value from the two papers. 
Ridge takes four arguments. The third argument is the k value you want to input. Then the last one set "nocons = False"
Standard ridge regression does not include and F-test, because it is meaningless. 

Test function is there to do F-test under Homoskedasticity. Takes 4 arguments: y, X, null, and k.

"null" is the restricted model that you want to test. Please input constant if you want the standard test. Otherwise please specify your restricted model. And X would be your unrestricted model. K is the bias you would like to include. 

Please contact me by 
cai.ming@live.com 
if you have any questions. 

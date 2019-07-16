Error 1
error:- Temperature was not of integer datatype, spliting of the temperature was incorrect .
approach:- Understood the splitting of the temperature and made changes to split function of temperature in Main_Page.py .

Error 2
error:- KeyError.
approach:- Looked up "Key Error" in Google. I Understood A Python KeyError exception is what is raised when you try to access a key that isn’t in a dictionary (dict). Searched the code for any dict type found in "e2e_weather_shopper_conf.py" changed the key.

Error 3
error:- Conditional check
Could not obtain the cheapest product with the filter condition 'aloe'
Check the screenshots to see if there was at least one item that satisfied the filter condition.

Approach : Traced back to the condition for selecting the minimum product of "Aloe" changed the condition in Product_Object.py  
product.price <= min_price

Error 4
error:- TypeError("unsupported operand type(s) for -: 'NoneType' and 'NoneType'")
I think the function is not returning anything

approach : Traced through the functions in Product_Object and founded that it was not returning any value .
Fix :- Added the return statement.

Error 5
:Stop_Test_Exception('Stopping test because: Automation is not on the cart page') 

I think that its not able to locate the xpath of checkout button.
approach : In the error messages I founded out that the cart button was not able to get clicked, due to the xpath issue(//button[@onclick='goTocart']) I traced it back to the locators_conf.py file and checked if the xpath works or not.

Fix:- changed the xpath to [//button[@onclick='goToCart']


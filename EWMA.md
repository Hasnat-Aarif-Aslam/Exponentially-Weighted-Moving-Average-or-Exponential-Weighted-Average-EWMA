**What is EWMA?**

EWMA is a technique through which we can identify hidden patterns in time series based data.

* As the time passes, the weightage of a particular point decreases.

* The weightage of a previous point is less than the weightage of a point after it.

* We will keep beta = 0.9, as it's the most widely used value

![image](https://github.com/user-attachments/assets/c44f9a76-5e71-4efd-bec5-622d05fe5534)


**What is the purpose of this beta?**
* More the value of beta, more we value the previous points

* if we use beta = 0.9, the value 10 indicates that it will now behave as if we have calculated the average of last 10 points for that particular point
![image](https://github.com/user-attachments/assets/4f4348e3-55e5-4891-b29e-2a1b66a72c00)

* if we use beta = 0.5, now 2 indicates we have calculated the average of last 2 points for that particular point
![image](https://github.com/user-attachments/assets/654691e7-9766-41db-8654-1052a2d6009d)


**beta effect in action**
* at 0.98, it is adjusting more with respect to the past points
![image](https://github.com/user-attachments/assets/3a60fe02-d1e1-4127-b895-626e0fdd8263)

* at 0.1, it is adjusting more with respect to the current points
![image](https://github.com/user-attachments/assets/2ccbca73-358e-4717-8fba-491054024f23)

alpha = 1-beta
![image](https://github.com/user-attachments/assets/3a45e61c-07da-4eb1-8b46-0cceaa2c08b1)





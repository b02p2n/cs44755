java c
MGMT 472, Fall 2024 
Homework 4 
Problem 1: A call center 
A process flow map for a call center is provided below. Here'show this process works.
Customers with questions about this company's products call an 800 number. During atypical 8- hour day shift, the time between calls can be approximated by an exponential distribution with a mean of 4 minutes. The call center has 10 phone lines and hence can handle up to 10 calls at once. If a call arrives and all 10 lines are in use, then the caller gets a busy signal and has to call back later. If a call arrives and fewer than 10 lines are in use, then the call goes directly to a customer service (CS) person, if one is available, and otherwise is put on hold. The amount of time for a CS person to handle a call, once answered, can be approximated by a normal distribution, with a mean of 10 minutes and a standard deviation of 2 minutes. 
Note: Because there are only 10 phone lines, the number of CS people plus the capacity of Line must be 10. 
Process Flow Map for Call Center 

Question: Management wants to determine how many CS people to use during the day shift so that two things are both true: the mean number of minutes a person waits is less than 2 minutes and the service level is at least .99. Consider using from one to five CS people. For each possibility, run 50 simulations of an 8-hour day shift and record the mean cycle time through   Line. Assume that the initial number of callers on hold at the beginning of the day shift can be approximated by a normal distribution with a mean of 2 and a standard deviation of.5 (SimQuick will round to the nearest integer). How many CS people would you recommend for the day shift?
Problem 2 
This problem builds on the electronics superstore and warehouse examples, by considering them simultaneously in amulti-level supply chain. Thus, the store management now has control of two levels of the supply chain. The key question is still: How much and when to order? However, management now must consider inventory that occurs in several places of the process代 写MGMT 472, Fall 2024 Homework 4
代做程序编程语言, including the delivery trucks!
Consider a company that manages two electronics stores that sell the same popular handheld computer. Orders areplaced to a regional warehouse, also owned by this company. The regional warehouse places orders to the manufacturer (which is not owned by the company). The amount of time to receive an order at either store can be approximated by a normal distribution with a mean of 1 day and a standard deviation of.1 days. The amount of time to receive an order at the warehouse can be approximated by a normal distribution, with a mean of 4 days and a standard deviation of.2 days. The mean demand for this computer at each store is five computers per day (both stores are open 10 hours per day, 7 days per week). The demand is expected to remain the  same at both stores for the next 60 days.
Management wants to use areorder point scheme at the stores and the warehouse. Their goal is to achieve at least a 95% service level at each store at minimum cost. The ordering costs are $75  everytime a storeplaces an order to the warehouse and $150 everytime the warehouse places an order to the factory. It also costs $.50 per day for every computer in inventory at a store, and $.10 per day for every computer in inventory at the warehouse. We assume it also costs $.50 per day for every computer in transit from the warehouse to a store. 
Let time units in SimQuick represent hours. Thus, the delivery time to the stores from the warehouse is modeled by Nor(10,1) and the delivery time to the warehouse from the factory is modeled by Nor(40,2).
Finally, let’s consider how to calculate the cost of inventory in transit from the warehouse to the store. To begin, we calculate the mean inventory in transit to Store 1 (this is done similarly for Store 2):
Build the SimQuick model for this problem. For each scenario (row) in the following table, run 40 simulations and report the mean of the overall mean service levels for the two stores and the estimated total cost. Which scenario should management adopt?


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

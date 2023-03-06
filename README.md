# Computer-Simulation
# Simulation of a call center in Excel

A government center has a 24-hour call center. This center has 25 telephone lines. The workflow is such that incoming calls and audience requests are divided into three
processes: sales, technical support, and order review. If all 25 lines are busy when a call is made, the call will be left out of the system, otherwise it will be placed
in the answering queue.

- The time interval between two incoming calls has an exponential distribution with an average of 0.857 minutes.
- The type of incoming call is determined by uniform distribution in the interval (0.6 and 0.1).
- 8% of requests are related to order review, 16% are related to sales and 76% are related to support.
- The order check has a triangular distribution with parameters (2, 3, and 4).
- Sales has a triangular distribution with parameters (4, 15 and 45).
- In support, the expert's secondary message is characterized by a uniform distribution in the interval (0.5 and 0.1).

![Screenshot (532)](https://user-images.githubusercontent.com/126339266/223163443-aedfa045-a8b3-4d51-8dcf-4d91be040d4d.png)

In this project, the above center should be simulated with the mentioned conditions. The duration of simulation is 1000 minutes and the system will be closed after 1000
minutes. The following items have been checked and calculated:

A) Number of rejected calls
b) Average number of calls in progress
c) Service period
d) Waiting period in the system

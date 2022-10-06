# Notes-10-
Automatic Scaling &amp; Monitoring
//overview;
load balance: distributing computational workloads - between 2 or more computers - divide network traffic - reduce strain on each server
load balancer: hardware based or software based
static load - quick to set up but can result inefficiencies
dynamic load - difficult to configure
Server failover is critical for reliability: a server crash could bring down a website or application if there is no backup in place. It is critical that failover occurs quickly to avoid a service interruption
There are numerous IT monitoring services available. System monitoring, dependency monitoring, and many other topics have received the most attention.
//autoscaling;
So that an application typically scales based on load balancing serving capacity, auto scaling and load balancing are related.
Both application auto scaling and load balancing reduce backend tasks such as monitoring server health, managing traffic load among servers, and increasing or decreasing servers as needed.
//advantages
cost, security, and availability 
// Predictive autoscaling is especially useful for:
-Detecting large, imminent spikes in demand and readying capacity slightly in advance
-Coping with large-scale, regional outages
-Offering more flexibility in scaling out or in to respond to variable traffic patterns throughout the day
//Horizontal vs Vertical auto scaling 
In order to scale, horizontal auto scaling involves adding more servers or machines to the auto scaling group. Vertical auto scaling refers to scaling by adding more power rather than more units, such as additional RAM.
Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time

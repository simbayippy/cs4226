# CS4226 Midterm Practice Questions

## Question 1
Consider an M/M/1 queueing model with parameters λ and μ and the following variation: after completing the service at the server, every customer will have a probability of p independently of joining back to the end of the queue immediately. Suppose μ = 1 and p=0.2. What is the minimum external arrival rate λ that will make the system unstable?

A: 0.5
B: 0.6
C: 0.7
D: 0.8
E: 0.9

## Question 2
Consider an M/M/1 queueing model with parameters λ and μ and the following variation: after completing the service at the server, every customer will have a probability of p independently of joining back to the end of the queue immediately. Suppose μ = 1 and p=0.2. Assume that the external arrival rate satisfies λ = 0.4, and the system has reached a stable state after running for a long time. The utilization of the server equals ______.

## Question 3
Consider an M/M/1 queueing model with parameters λ and μ and the following variation: after completing the service at the server, every customer will have a probability of p independently of joining back to the end of the queue immediately. Suppose μ = 1 and p=0.2. Assume that the external arrival rate satisfies λ = 0.4, and the system has reached a stable state after running for a long time. What is the probability that a random observation finds exactly 1 customer waiting in the queue? The probability is ______.

## Question 4
Consider an M/M/1 queueing model with parameters λ and μ and the following variation: after completing the service at the server, every customer will have a probability of p independently of joining back to the end of the queue immediately. Suppose μ = 1 and p=0.2. Assume that the external arrival rate satisfies λ = 0.4, and the system has reached a stable state after running for a long time. On average, how long will each customer stay in this feedbacked M/M/1 system before departing?

A: 2
B: 2.5
C: 3
D: 3.5
E: 4

## Question 5
Consider an M/M/1 queueing model with parameters λ and μ and the following variation: after completing the service at the server, every customer will have a probability of p independently of joining back to the end of the queue immediately. Suppose μ = 1 and p=0.2. Assume that the external arrival rate satisfies λ = 0.4. There are two types of events that will change the number of customers in the system: 1) a new arrival from outside the system, and 2) a departure of customer that leaves the system without rejoining. If a random observation finds that the server is busy, what is the probability that the next event that will change the number of customers is a new arrival of packet from outside, i.e., type 1)?

A: 2/7
B: 1/3
C: 1/2
D: 2/3
E: 5/7

## Question 6
Suppose I need to get connections to two independent servers. The time for getting a connection established to the two servers S1 and S2 follow an exponential distribution with parameters μ1 and μ2, respectively. If μ1=1 and μ2=1, and T is the random amount of time that I need to wait till I obtain both connections. How long on average does it take for me to obtain connections from both servers if I start establishing the connections from both servers simultaneously? E[T] = ______.

## Question 7
Suppose I need to get connections to two independent servers. The time for getting a connection established to the two servers S1 and S2 follow an exponential distribution with parameters μ1 and μ2, respectively. If μ1=1 and μ2=3, and if I start establishing the connections from both servers simultaneously, what is the probability that I establish a connection to server S1 first? This probability equals ______.

## Question 8
Consider the Jackson network shown in the image below. If p=0.8 and q=0.5, what are the effective rates into the two subsystems? λ1 = ______ and λ2 = ______.

![Jackson Network](https://example.com/jackson_network.png)

## Question 9
Consider the Jackson network shown in the image above. If p=q<1, then the effective rates λ1 and λ2 into the two subsystems satisfy:

A: λ1 must be larger than λ2
B: λ1 must be smaller than λ2
C: λ1 must be equal to λ2
D: λ1 cannot be equal to λ2

## Question 10
Consider a network path with four links as shown in the image below. There are four traffic flows: flow f1 traverses links 1, 2 and 3; flow f2 traverses links 3 and 4; flow f3 traverses links 1 and 2; flow f4 traverses links 2,3 and 4. Suppose the demand of the four flows are d1 = 2, d2 = 4, d3 = 1 and d4 = 3 (Mbps), respectively. Calculate the weighted max-min fair allocation x = (x1, x2, x3, x4) for the four flows, where the weights of the four flows are φ = (φ1,φ2,φ3,φ4) = (1,2,3,4). 

![Network Path](https://example.com/network_path.png)

x1= ______ (Mbps)
x2= ______ (Mbps)
x3= ______ (Mbps)
x4= ______ (Mbps)

## Question 11
Referring to the network path shown in the image above, under the weighted max-min fair allocation, where the weights of the four flows are φ = (φ1,φ2,φ3,φ4) = (1,2,3,4), which of the following includes all the bottleneck links for flow f1?

A: C1 only.
B: C2 only.
C: C3 only.
D: C1 and C2 only.
E: None.

## Question 12
Referring to the network path shown in the image above, under the weighted max-min fair allocation, where the weights of the four flows are φ = (φ1,φ2,φ3,φ4) = (1,2,3,4), which of the following includes all the bottleneck links for flow f2?

A: C1 only.
B: C2 only.
C: C4 only.
D: C1 and C4 only.
E: None.

## Question 13
Referring to the network path shown in the image above, under the weighted max-min fair allocation, where the weights of the four flows are φ = (φ1,φ2,φ3,φ4) = (1,2,3,4), which of the following includes all the bottleneck links for flow f3?

A: C1 only.
B: C2 only.
C: C3 only.
D: C2 and C3 only.
E: None.

## Question 14
Referring to the network path shown in the image above, under the weighted max-min fair allocation, where the weights of the four flows are φ = (φ1,φ2,φ3,φ4) = (1,2,3,4), which of the following includes all the bottleneck links for flow f4?

A: C2 only.
B: C3 only.
C: C4 only.
D: C3 and C4 only.
E: None.

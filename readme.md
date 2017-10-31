# Queue Example

## Objective
Simulate an atm queue, based on the following rules:
The probability of a client stay on the atm is:

1.  1 minute -> 15%
2.  2 minutes -> 50%
3.  3 minutes -> 25%
4.  5 minutes -> 10%

During the period of 1 minute, the probability of arriving clients is:

1.  0 clients -> 30%
2.  1 client -> 40%
3.  2 clients -> 25%
4.  3 clients -> 5%

A client will leave if there's more than 5 people in the queue.


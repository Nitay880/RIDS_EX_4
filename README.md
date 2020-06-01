#                Asynchronous agreement

the following protocol solves an asynchronous agreement with N = 2f + 1 
servers and an adaptive adversary that can cause f omission failures.

![](RIDS_PROJECT.gif)


The following project is the final project of reliability in distibuted systems

# Server Class
- A server that is connected to the mediator
- runs N different worlds and comminicates in them seperately
- Is sending his value in order to promote it
- decides iff N-F-1 servers are agree on the same value
# Mediator Class
- delays messages to a random period of time 
- mediates between the servers - i.e all messages are going through the mediator in their path to the other servers




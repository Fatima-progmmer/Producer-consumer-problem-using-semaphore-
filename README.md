# Producer-consumer-problem-using-semaphore-

## Aim

To write a program to simulate producer - consumer problem 


## Description

The Producer-Consumer Problem is a synchronization problem. It involves a fixed-size buffer where the producer produces items that are consumed by a consumer process. One solution to the Producer-Consumer Problem uses shared memory, allowing the producer and consumer processes to run concurrently.

There must be a variable to a buffer of items that can be filled by the producer and emptied by the consumer. The buffer will reside in a region of memory that is shared by the producer and consumer processes.

The producer and consumer must be synchronized so that the consumer does not try to consume an item that has not been produced.

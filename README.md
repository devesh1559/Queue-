# Queue
## AIM
To implement queue and perform Enqueue and Dequeue
## THEORY
Queue is a linear data structure. It has seperate ends to perform insert and delete operations. Two ends of queue are called Front and rear
 The insert operation is known as enqueue and delete operation is known as dequeue.
Queue finds application in Ticketing system, Task scheduling and Printing Queue
There are three types of queue data structure. These are linear queue, circular queue and priority queue

## Algorithm
ENQUEUE
Check if queue is full
if full produce error
else
increament rear pointer
store data at rear 
if inserting int element
increament front by 1

DEQUEUE
if front==-1//front>rear
queue empty
exit
else
queue[front]=0
front=front+1





## Conclusion
It works on the principle of FIFO First in first out.

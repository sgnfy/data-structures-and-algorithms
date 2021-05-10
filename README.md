# Cracking the coding interview

__Table of contents__

- [(VI) BigO](#vi-big-o)
    - ...
    - [Amortized Time](#amortized-time)
    - [Log N Runtimes](#log-n-runtimes)


## (VI) BIG O

### Amortized Time 
[ref.](https://medium.com/@satorusasozaki/amortized-time-in-the-time-complexity-of-an-algorithm-6dd9a5d38045)

When the array in it hasn’t reached its capacity and still has enough space to insert items.

![array has enough space](amortizedTime-1.png)

When the array in it has reached its capacity and need to re-create itself with the doubled size.

![array is full](amortizedTime-2.png)

The insertion takes O(n) when the capacity has been reached, and the amortized time for each insertion is O(1).

### Log N Runtimes
TODO
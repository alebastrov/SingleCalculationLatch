This is simple implementation of latch. When you need to skip some calculation for sumultaneous threads running at the same time and peforming the same calculation 
(for instance calculate the same Fibonacci number 13) you may rely pn this code to make the calculation be performing in ONLY single thread.

As soon as calculation is ready, all waiting threads will be provided with same result.

It may significantly decrease CPU load

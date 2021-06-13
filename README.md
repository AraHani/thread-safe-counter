# thread-safe-counter

![화면 캡처 2021-06-13 202100](https://user-images.githubusercontent.com/82162578/121805766-8c370780-cc87-11eb-9585-f664d89992fd.jpg)

##Result
Mutex (tscounter.c) is faster than semaphore (semaphore.c)

##Anylysis
In these codes, Mutex is faster than semaphore because mutex only access 1 thread but semaphore can access the number of the semaphore variables.



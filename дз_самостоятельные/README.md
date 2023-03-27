# Comments
## Task 2, semester 1
In the last task, I implemented the implicit Runge-Kutta method, the Butcher table itself is taken from Lobanov's book with tasks. I found the coefficients by solving an implicit equation with respect to them using the Newton method, sometimes the initial approximation of its roots was incorrect, which caused the entire RK algorithm to go into recursion, nevertheless, part of the solution was preserved and I had already visualized it. <br>
The method from the package uses a method intermediate between the backward differentiation formula and the Adams method. <br>
As it turned out at the handover, the task was set incorrectly in my task book, there should have been a 2nd derivative in y and other initial conditions, the implicit RK should be redone in this case, the explicit Dormand - Prince was repaired

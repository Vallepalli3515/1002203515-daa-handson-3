# 1002203515-daa-handson-3
function x = f(n)
   x = 1;
   for i = 1:n
        for j = 1:n
             x = x + 1;
Find the runtime of the algorithm mathematically (I should see summations).
Time this function for various n e.g. n = 1,2,3.... You should have small values of n all the way up to large values. Plot "time" vs "n" (time on y-axis and n on x-axis). Also, fit a curve to your data, hint it's a polynomial. 
Find polynomials that are upper and lower bounds on your curve from #2. From this specify a big-O, a big-Omega, and what big-theta is.
Find the approximate (eye ball it) location of "n_0" . Do this by zooming in on your plot and indicating on the plot where n_0 is and why you picked this value. Hint: I should see data that does not follow the trend of the polynomial you determined in #2.
If I modified the function to be:
x = f(n)
   x = 1;
   y = 1;
   for i = 1:n
        for j = 1:n
             x = x + 1;
        y = i + j;
4. Will this increate how long it takes the algorithm to run (e.x. you are timing the function like in #2)? 

5. Will it effect your results from #1?

6. Implement merge sort, upload your code to github and show/test it on the array [5,2,4,7,1,3,2,6].

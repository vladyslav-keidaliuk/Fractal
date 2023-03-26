# Fractal
A simple fractal in 100 lines of code 

This fractal is built according to a simple rule:

It starts with the first largest circle. Then each iteration 4 circles (top, left, right, bottom)
with radius 2 times less than the previous one are pulled up to the biggest circle. 
Each iteration will produce a total of 2^n circles (n is pair power).
Also, with each iteration, the line thickness changes.

Consider stepwise iterations (e.g., initial circle radius is 150 px and number of iterations = 4):
1: 1 circle with radius 150 px
2: 4 circles with radius 75 px
3: 16 circles with a radius of 37.5 px
4: 64 circles with a radius of 18.75 px.

In total we will have : 2^0 + 2^2 + 2^4 + 2^6 = 85 circles on the canvas.

![image](https://user-images.githubusercontent.com/102413334/227795212-ecae0de0-c7a8-4bd3-beb8-448b1e750501.png)
Number of iteration = 6, line thickness = 10;

![image](https://user-images.githubusercontent.com/102413334/227795223-ff084626-2a93-4fba-a3ff-1682cbbbe57d.png)
Number of iteration = 5, line thickness = 30;

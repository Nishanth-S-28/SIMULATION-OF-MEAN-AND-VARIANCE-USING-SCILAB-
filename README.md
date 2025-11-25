# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-
__AIM:__

To write a program for mean, variance and cross correlation in SCILAB and verify the output. 

__EQUIPMENTS NEEDED:__

.Computer with i3 Processor 

.SCI LAB 

__ALGORITHM:__

1. Define the Function: Specify the function you want to simulate. For example, 
f(x)=sin⁡(x)f(x)=sin(x) or any other function. 
2. Generate Sample Points: Decide on the range and the number of sample points. Generate 
these sample points within the desired range. 
3. Evaluate the Function: Compute the function values at each of these sample points. 
4. Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the 
mean and variance of the computed function values. 
5. Display Results: Output the computed mean variance and Cross Correlation 

__PROCEDURE:__ 

1.Refer Algorithms and write code for the experiment. 

2.Open SCILAB in System 

3.Type your code in New Editor 

4.Save the file 

5.Execute the code If any Error, correct it in code and execute again 
  
6.Verify the generated results

__PROGRAM:__
```c



clc;
clear;

// ----- INPUT SIGNALS -----
x = [1 2 3 4 5];
y = [2 3 4 5 6];

// ----- MEAN -----
mean_x = mean(x);
mean_y = mean(y);

// ----- VARIANCE -----
var_x = variance(x);      // by default, Scilab uses unbiased estimation (N-1)
var_y = variance(y);

// ----- CROSS CORRELATION -----
cross_xy = xcorr(x, y);   // full cross-correlation

// ----- DISPLAY RESULTS -----
disp("Mean of x = " + string(mean_x));
disp("Mean of y = " + string(mean_y));

disp("Variance of x = " + string(var_x));
disp("Variance of y = " + string(var_y));

disp("Cross-correlation (x,y):");
disp(cross_xy);
```

__OUTPUT GRAPH:__

![IMG_20251125_125223](https://github.com/user-attachments/assets/080af26d-7414-483a-90e3-da4e82e5da4a)



__RESULT:__

Thus the mean and variance ,cross correlation is verified using SCILAB .

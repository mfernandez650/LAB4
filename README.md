%Melissa Fernandez 
%Engineering 215 
%September 21, 2016
%Lab 04 - Introduction to MATLAB Programming
clc
format compact
disp('Chapter 3 - Exercise 14')
    %Create coordinate variables and plot a green '+'
    x1 = input('Your x value is:');
    y1 = input('Your y value is:');
    figure(1)
    plot(x1,y1,'g+')
disp('Chapter 3 - Exercise 15')
    %Using 10 points in this range
    x2 = linspace(0,pi,10);
    y2 = sin(x2)
    figure(2)
    plot(x2,y2)
    %Using 100 points in this range
    x3 = linspace(0,pi,100);
    y3 = sin(x3)
    figure(3)
    plot(x3,y3)
disp('Chapter 3 - Exercise 20')
    matrix1 = randi([50,100],3,6)
    matrix2 = randi([50,100],2,6)
disp('Chapter 3 - Exercise 24')
    %converts from MWh to GJ
    function mwh_to_gj = conv_power_mwh_to_gj(n)
    mwh_to_gj = n.*3.6;
    fprintf('When MWh is %.2,',n);
    fprintf('the GJ will be %.2f\n',mwh_to_gj);
    end   
disp('Chapter 3 - Exercise 34')

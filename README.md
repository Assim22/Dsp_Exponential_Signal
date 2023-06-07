# Dsp_Exponential_Signal
This is a simple project for Dsp to show the figure of Exponential signal . Find the project video on [YouTube](https://youtu.be/hwhiNH-LDyk)
```
% Name Assim Abdelnour
clc;
clear all: %delete all pervious variable
close all % close all space work 
%% Generation Signal
t = 0:0.1:6;
x = exp(t)
plot(t,x)
%stem(x)
xlabel('time');
ylabel('Amplitude');
title('Exponential Signal');
%% Generation sign
```
## For stem(t,x) the figure looks like:
![Exponential1](https://github.com/Assim22/Dsp_Exponential_Signal/assets/119833997/7b867739-fec8-4073-b880-a7ed9e9f396a)

## For plot(t,x) the figure looks like:
![PlotRealValuedExponentialFunctionExample_01](https://github.com/Assim22/Dsp_Exponential_Signal/assets/119833997/bc722cd4-e153-472a-b727-148736d457b0)


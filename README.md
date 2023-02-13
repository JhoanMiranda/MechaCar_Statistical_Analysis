# MechaCar_Statistical_Analysis


# Linear Regression to Predict MPG

  ##  1.Which variables/coefficients provided a non-random amount of variance to the mpg values in the             dataset?
    
#### •	(intercept)

#### •	mechaCar_table$ground_clearance

#### •	mechaCar_table$vehivle_length

 ##   2.Is the slope of the linear model considered to be zero? Why or why not?
    
   #### Does not especify to be 0 because the solpe of the linear model is represented by the variable in the model wich is vehicle_leng and ground_clearence and but ground clearence seems not to be 0
    
    
  ###  Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  
  #### Yes showed by R-squared value of 0.7149. The adjusted R-squared of 0.6825 shows to be a good fit to the data but not perfect.
    
![Screenshot (131)](https://user-images.githubusercontent.com/114957364/218589349-7443c4fd-1bb2-44e0-a237-9b5a52e86554.png)

# Summary Statistics on Suspension Coils

The collected data is the result of different lots of suspension coils, which was tested to determine if the results are consistent across the lots 

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?



![Screenshot (133)](https://user-images.githubusercontent.com/114957364/218597759-fc266a01-6f0b-4d52-9cbc-2004791b48fa.png)


![Screenshot (134)](https://user-images.githubusercontent.com/114957364/218598866-79ac8e1c-3706-4e19-990f-0b5f95bf4276.png)


![Screenshot (135)](https://user-images.githubusercontent.com/114957364/218598876-e4559e03-7e9e-4a39-bedd-a7fcfee6ca56.png)


no because exceeded the 100 psi across neither 3 lot pass the test individually
## Study Design: MechaCar vs Competition
Using the knowledge acquired we can create an analysis aiming to performance and efficiency
What metric or metrics are you going to test? fuel consumption 

What is the null hypothesis or alternative hypothesis? 
null hypothesis in this case is that MechaCar have no difference with the competitors.
alternate hypothesis in this case MechaCar could outperform in more than 1 of the metrics gathered. 

What statistical test would you use to test the hypothesis? And why?

 Could be solved comparing the means and for that we could use the t-test .

What data is needed to run the statistical test?
It depends on the purpose of the analysis, but we can collect data on internet, company’s research team etc.


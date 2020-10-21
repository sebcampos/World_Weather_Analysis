# Linear regression /functions

    from scipy.stats import linregress

    (slope,intercept,r_value,p_value,std_err)=linregress(x_axis,y_axis)

- in statistics the p value is used to determine significance of results. in most cases scientists like to use a significance level of 0.05
    - a linear regression with a p-value >0.05 is statistically significant
    - a linear regression with a p-value <0.05 is statistically significant
    - p-values can be used to justify rejecting a null hypothesis 

 
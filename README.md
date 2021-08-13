# Control_Chart-Quality_Control
Introduction to control chart, how data can be evaluated to be statistically under control or not.

1.	Importing Relevant Libraries:
     Pandas	Numpy	Matplotlib

2.	Making a copy set of Data

3.	Mean and Range of dataset:

`r_1 = np.mean(B1['visitors'])`

`range_r_1 = max(B1['visitors']) - min(B1['visitors'])`

4.	Calculating Upper Limit and Lower Limit:

`ucl_r_1 = 1.5*r_1`

`lcl_r_1 = 0*B1['visitors'] `

5.	Plotting charts:

`B1["visitors"].plot(marker="o")`

`B1["ucl_r"].plot(color='b')`

`B1["lcl_r"].plot(color='k')`

`B1["rbar"].plot(color='r')`

6.	Imp. Values:
           
7.	Out of range calculation: 

`for i in B1["visitors"]:
    	    if i>ucl_r_1:
             count =count+1`



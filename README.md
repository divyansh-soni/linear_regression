# linear_regression
   ##  overview
    Suppose you are the CEO of a restaurant franchise and are considering diﬀerent cities for opening a new outlet. 
    The chain already has trucks in various cities and you have data for proﬁts and populations from the cities.
    You would like to use this data to help you select which city to expand to next. Make predictions on proﬁts 
    in areas of 35,000 and 70,000 people.
    
   ## intution
     As, more is the population of a city, more is the profit and hence it is more likely to be expanded. right?
     Also from the data set, we can infer that the profit is a function of population only. Since from the given 
     data set, we have to learn and then predict the output for given population, so it is a regression problem.
  
  #### ploting the data to visualise it
     Now, let's plot the given data set. i.e., profit vs population graph. It looks like this...
![untitled](https://user-images.githubusercontent.com/31219586/34671025-c10ad6b8-f49e-11e7-9c97-ad1efa3ffe7c.png)
   
   #### Creating the regression model
     since, we have to solve this problem by linnear regression and moreover it is univariate. so, let's take our
     hypothesis  function as ...
 ![capture](https://user-images.githubusercontent.com/31219586/34670901-41879df4-f49e-11e7-8d72-3b755288ada0.PNG)

clearly, sum_sqared_function is written as...
 
![image](https://user-images.githubusercontent.com/31219586/34671179-876b954a-f49f-11e7-9a04-9fd86efca112.png)    
     
  now, we need to minimize this sum_squared_function by using gradient descent i.e., choosing the values of theta 
  so that function assumes minimum value. this can be done by gradient descent method. i.e., updating values of 
  theta as..

![image](https://user-images.githubusercontent.com/31219586/34671461-bf4a932a-f4a0-11e7-921e-477c3eab70ae.png)

   ##Usage
 Now,we get our values of theta, for the hypothesis function. So, we can predict the profit for the required values.
 hence, 
      h(35,000)=theta0+theta1*(35,000)=
 and, h(70,000)=theta0+theta1*(70,000)=      

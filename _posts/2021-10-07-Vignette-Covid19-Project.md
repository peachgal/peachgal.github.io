### For the [GitHub page project repo](https://github.com/peachgal/vignette_project) 

### For the [usual rendered project repo](https://peachgal.github.io/vignette_project/)

1. Explain what I did in the project. 
   
   I created and customized some functions to query the Covid-19 data. I explained how to input the arguments for those functions and how to use them. I gave examples on what the API URL is supposed to look like for each function call. What to do and what not to do. I also gave a list of all the arguments in each customized function and what other user-friendly forms these arguments can take. I spent a lot of time trying to show users how to use my functions to query the Covid-19 data from the API site.
   
   Then, upon receiving the data, I had to do a lot of data manipulation to combine some data sets, make some computations within the data and create some variables. I had to make the categorical variables as factors so that the levels will appear in the pots later in the order I want. I created an infix function for my needs and that was awesome! Basically, I was curious about total active cases and deaths between different time groups and the effects of introduction of the Delta variants on them as well as the students going back to school event. So I had to make a lot of adjustments to talor my original data set for each of my contingency tables and the plots I made. 

2. Any interesting findings. 
   
   This may not be related to this question but before this project, we had a exam. By studying the exam, I re-learnt some tiny details that I had missed about R Markdown such as making a table in the plain text section. I discovered a lot of useful things I could implement in the project, and so I made notes of those for my project. 

   Upon completioin of the project, I realized that no wonder the State of North Carolina mandated on the wearing the mask again in mid-August (don't remember the exact time). When people around me kept saying the number of cases went up again in August. I never thought it would be as high as back in January 2021 because I never compare figures. I remember I was thinking it could not be as bad as earlier this year or last year. This Delta variant is indeed very contagious and virulent.  

3. What was the most difficult part of the logic and programming for you?

   The most difficult part of the overall project has got to be making the customized functions. To make it more user-friendly and be creative about what the different input arguments can the users supply with the functions I created. I created a lot of mini-functions to take in different forms of different inputs, and then I created each individual function for a specific type of query. I created nite of them. Then, at the end, af first, I used a lot of if/else functions in the wrapper function to wrap all of my customized functions together. It was very confusing even to myself. Then, I realized it did not have to be this complicated. So, I cut out a lot of mini-functions I created at the beginning and simplified my customized functions a bit so that my wrapper function is more readable. 
   
   There are a lot of named input arguments created. I had troubles on how to set the default values for each customized functions and at which part should I set them. I had to go back to homework 6 to see how I did it to wrap function within another function within another function. Programming wise is not hard, just need to research a lot on how to get what users/I want to the input arguments. To me, the logic part is what I had most difficulty with. It can be simple and straightforward or I could just wrap myself in a rabbit hole and spent a whole on how to link those functions together and still to no avail. I need to simplify things period.

4. What would you do differently in approaching a similar project in the future?
   
   I did not test on the API functions I made if they can take in a vector or a data frame. I think I would want to test it in a similar project in the future. I had ten queries for getting the data I wanted for this project using the functions I made. I had a lot of input arguments for the queries. I would like to put them in a list or a data frame and use lapply functions with it and my customized functions to see if it would work. 
   
   Other than that, I think I would like to perform some statistical analysis and run some tests to see if the differences I found between different timelines are really significant. 
   
   
   
### Contact me

[cwang51@ncsu.edu](mailto:cwang51@ncsu.edu) 
or 
[peachgal99@gmail.com](mailto:peachgal99@gmail.com)

---
title: Quiz 3 Solutions
subtitle: MGCR 271
author: Ramnath Vaidyanathan
widgets: [mathjax, quiz, bootstrap]
url: {lib: ../quiz1/libraries}
--- &radio

## Question 1

Given the least squares regression line $\hat{y} = 5 - 2x$


1. The relationship between x and y is positive.
2. _The relationship between x and y is negative_
3. There is no relationship between x and y
4. as x decreases, so does y.
5. None of the above.

*** .explanation

The slope of the line is -2, which is negative. So the relationship between x and y is __negative__.

--- &radio

## Question 2

A regression analysis between sales (in \\$1000) and advertising (in \\$100) resulted in the following least squares line:  $\hat{y} = 75 + 6x$  This implies that if advertising is \\$800, then the predicted amount of sales (in dollars) is:


1. \\$4875
2. _\\$123,000_
3. \\$487,500
4. \\$12,300
5. None of the above.

*** .explanation

Plugging x = 8 in the equation, we get y = 75 + 6 * 8 = 123. Hence sales equals \\$123,000.

--- &checkbox

## Question 3

Which of the following techniques is used to predict the value of one variable on the basis of other variables? Select ALL CORRECT answers


1. _Correlation analysis_
2. Coefficient of correlation
3. Covariance
4. _Regression analysis_

*** .explanation

We can use regression or correlation analysis to predict value of one variable based on the other.

--- &radio

## Question 4

In the first order linear regression model, the population parameters of the y-intercept and the slope are estimated, respectively, by:


1. _b0 and b1_
2. b0 and β1
3. β0 and b1
4. β0 and β1
5. None of the above.

*** .explanation

The population parameters are β0 and β1, but they are estimated in the regression by _b0 and b1_. Hence, the answer is (A).

--- &radio

## Question 5

The least squares method for determining the best fit minimizes:


1. total variation in the dependent variable
2. _sum of squares for error_
3. sum of squares for regression
4. All of these choices are true.
5. None of the above are true.

--- &radio

## Question 6

In order to predict with 98% confidence the expected value of y for a given value of x in a simple linear regression problem, a random sample of 15 observations is taken. Which of the following t-table values listed below would be used?


1. 1.35
2. 1.771
3. 2.16
4. _2.650_
5. None of the above.

*** .explanation

We will use a t-statistic based on p = 0.01 and df = 15 - 2 = 13. From the table, we get 2.6503.

--- &radio

## Question 7

The sample correlation coefficient between x and y is 0.375. It has been found out that the p-value is 0.256 when testing H0: ρ = 0 against the two-sided alternative H1: ρ ≠ 0. To test H0: ρ = 0 against the one-sided alternative H1: ρ > 0 at a significant level of 0.193, the p-value will be equal to


1. _0.128_
2. 0.512
3. 0.744
4. 0.872
5. None of the above.

*** .explanation

The p-value of a one-tailed test will be half the p-value of the two-tailed test. Hence it will equal 0.256/2 = 0.128.

---

## Sunshine and Melanoma

![Imgur](http://i.imgur.com/yVbmJ2H.png)

--- &radio

## Question 8

Determine the least squares regression line.

1. yhat =  1.115 - 1.846 x
2. yhat = 1.115 + 1.846 x
3. _yhat = -1.115 + 1.846 x_
4. yhat = 1.846 + 1.115 x
5. Cannot be calculated

*** .explanation





We know that $b_1 = r x s_y/s_x$ and $b_0 = \bar{y} - b_1 \times \bar{x}$. Plugging in values, we get $b_1 = sqrt(0.9231) \times 3.207/1.669$, which equals  1.8462. Hence, $b_0 = 9.5 - 1.8462 \times 5.75$, which equals  b0 = -1.1154. We can now write down the equation of the line as (C).

--- &radio

## Question 9

Estimate the number of skin cancer cases per 100,000 people who live in a state that gets 6 hours of sunshine on average.


1. _yhat = 9.961_
2. yhat = 12.191
3. yhat = 8.536
4. yhat = 4.844
5. Cannot be calculated

*** .explanation

Plugging x = 6 in the equation, we get $\hat{y} = -1.115 + 1.846 \times 6$, which gives us 9.961.

--- &radio

## Question 10

What does the value of the slope of the regression line tell you?


1. If the amount of sunshine x increases by one hour, the amount of skin cancer y increases by an average of 1.115 per 100,000 people.
2. If the amount of sunshine x increases by one hour, the amount of skin cancer y decreases by an average of 1.846 per 100,000 people.
3. If the amount of sunshine x decreases by one hour, the amount of skin cancer y decreases by an average of 1.846 per 100,000 people.
4. If the amount of sunshine x increases by one hour, the amount of skin cancer y increases by an average of 1.846 per 100,000 people
5. _Both (c) and (d) are correct._

*** .explanation

The regression slope tells us how the amount of skin cancer cases change per unit change in sunshine. The sign of the slope indicates that the relationship is negative implying that if one decreases, the other increases and vice-versa. Hence, both (c) and (d) are correct.

--- &radio

## Question 11

Calculate the residual corresponding to the pair (x, y) = (8, 15).


1. _1.347_
2. -0.883
3. 4.234
4. 7.926
5. Cannot be calculated

*** .explanation

We can compute $\hat{y}$ for x = 8 as  $\hat{y} = -1.115 + 1.846 \times 8$, which gives us 13.653. Hence, the residual is given by $y - \hat{y}$ which equals 1.347

--- &radio

## Question 12

The adjusted coefficient of determination is adjusted for the:


1. _Number of independent variables and the sample size._
2. Number of dependent variables and the sample size.
3. Coefficient of correlation and the significance level.
4. Number of regression parameters including the y-intercept.

--- &radio

## Question 13

In a multiple regression analysis, if the model provides a poor fit, this indicates that:


1. The coefficient of determination will be close to zero.
2. The standard error of estimate will be large.
3. The sum of squares for error will be large.
4. _All of these choices are true._
5. None of these choices are true.

--- &radio

## Question 14

Suppose a multiple regression analysis involving 25 data points has $S_e^2=1.8$ and SSE = 36. Then, the number of the independent variables must be:


1. 3
2. _4_
3. 5
4. 6
5. Cannot be calculated

*** .explanation

Given MSE = 1.8 and SSE = 36, we can compute dfE = SSE/MSE = 36/1.8 = 20. We know that dfE = N - C, where C is the number of coefficients in the regression including the intercept. Since N = 25, we get dfE = N - dfE = 25 - 20 = 5. The number of independent variables is thus one less than C, which gives us __4__.

--- &radio

## Question 15

In multiple regression analysis, the ratio MSR/MSE yields the


1. t-test statistic for testing each individual regression coefficient.
2. _F-test statistic for testing the validity of the regression equation._
3. Coefficient of determination.
4. Adjusted coefficient of determination.
5. F critical value for testing the validity of the regression equation.

--- &radio

## Question 16

In order to test the validity of a multiple regression model involving 5 independent variables and 30 observations, the numerator and denominator degrees of freedom for the critical value of F are, respectively,


1. 5 and 30
2. 6 and 29
3. _5 and 24_
4. 6 and 25
5. 5 and 25

--- &radio

## Question 17

A multiple regression model has the form  yhat = 8 + 3x1 + 5x2 - 4x3. As x3 increases by one unit, with x1 and x2 held constant, the y on average is expected to;


1. increase by 1 unit.
2. increase by 12 units.
3. _decrease by 4 units._
4. decrease by 16 units.
5. Increase by 4 units

*** .explanation

The coefficient of x3 is -4. So if x3 increases by one unit, y on average is expected to decrease by 4 units.

--- &radio

## Question 18

For a multiple regression model, the following statistics are given: Total variation in y (SST) = 500, SSE = 80, and n = 25. Then, the coefficient of determination is:


1. _0.84_
2. 0.16
3. 0.3125
4. 0.05
5. 0.95

*** .explanation

We know that $R^2 = 1 - SSE/SST$. Plugging in the given values, we get $R^2 = 1 - 80/500$, which gives us 0.84

--- &radio

## Question 19

In a multiple regression model, the following statistics are given: SSE = 100, R2 = 0.995, k = 5, and n = 15. Then, the coefficient of determination adjusted for degrees of freedom is:


1. 0.930
2. 0.9
3. 0.955
4. 0.855
5. Cannot be calculated.

*** .explanation





The adjusted Rsquare is given by 1 - (SSE/dfE)/(SST/dfT). We also know that $R^2 = 1 - SSE/SST$. So SSE/SST = 1 - $R^2$ = 0.005. We also have dfE = `15 - (5 + 1)` and dfT = `15 - 1`. Plugging everything in, we get $1 - 0.005 \times 9/14$, which gives us 0.9968.

NOTE. Since the correct answer was not in the list of options, one point was awarded to everyone.

---

## Real Estate

A real estate builder wishes to determine how house size is influenced by family income, family size, and education of the head of household. House size is measured in hundreds of square feet, income is measured in thousands of dollars, and education is measured in years. A partial computer output is shown below.

---

<img src=http://i.imgur.com/Bcc9kEn.png height=200></img>

--- &radio

## Question 20

What is the value of the coefficient of determination R2 for house size?

1. 86.5% of the variability in house size is explained by this model.		
2. _74.8% of the variability in house size is explained by this model._		
3. 72.6% of the variability in house size is explained by this model.
4. Both (a) and (b) are correct
5. The percentage cannot be calculated from the information provided.

*** .explanation

The R2 can be calculated from the ANOVA table as $R^2 = 3605/4820$, which gives us 0.7479.

--- &radio


## Question 21

Which of the independent variables in the model are significant at the 2% level?

1. Family income
2. Family income and education.
3. Family size and education.
4. _Family income and family size._
5. None of the variables are significant at the 2% level.

*** .explanation

Using the coefficient table, we can compute the t statistics for each of the independent variables and compare it with the critical t statistic corresponding to probability of 0.01 (because it is two-sided) with df = 50 - 4 = 46. This gives us that family income and family size are the significant predictors at the 2% level.

--- &radio

## Question 22

What is the predicted house size for an individual earning an annual income of $40,000, having a family size of 4, and having 13 years of education?

1. 24.88
2. 17946
3. _2488_
4. 28.14
5. None of the above.

*** .explanation

We can plug in the values into the regression equation to get -1.6335 + 0.4485 x 4  + 4.2615 x 4  - 0.6517 x 13 which gives us 24.8804. Since y is measured in 100s of square feet, the answer is 2488 sqft which corresponds to (C).



--- &radio

## Question 23

What minimum annual income would an individual with a family size of 4 and 16 years of education need to attain a predicted 10,000 square foot home?

1. \\$211
2. \\$204.57
3. _\\$211.85_
4. \\$204
5. _None of the above._

*** .explanation

Once again, we have 100 = -1.6335 + 0.4485 x I  + 4.2615 x 4  - 0.6517 x 16. Solving for I, we get I = (100 - (-1.6335  + 4.2615 * 4  - 0.6517 * 16))/0.4485, which gives us 211.8499. Hence, the answer is 211.85 (in thousands of dollars).

NOTE. Full credit was given to those who chose none of the above, since the question does not clearly specify the units for the answer.

--- &radio

## Question 24

What is the value of the calculated F-test statistic that is missing from the output for testing whether the whole regression model is significant?

1. 33.41
2. _45.53_
3. 34.15
4. 46.52
5. None of the above

*** .explanation

The F-statistic can be calculated as MSR/MSE. We get MSR = 3605.773/3 and MSE = 26.396. Hence we get F = 45.53.

--- &radio

## Question 25


Interpret the value of the Adjusted R-Square.

1. The Adjusted R-Square is defined as the variability in house size is explained by this model, taking into account the most important variable and the sample size.
2. _The Adjusted R-Square is defined as the variability in house size is explained by this model, taking into account the number of variables (3) and the sample size._
3. The Adjusted R-Square is defined as the variability in house size is explained by this model, taking into account the correlation between the variables (3) and the sample size.
4. All the above are acceptable interpretations.
5. None of the above interpretations are acceptable definitions.

--- &radio

## Question 26

What are the regression degrees of freedom that are missing from the output?

1. 4, 46
2. _3, 46_
3. 4, 45
4. 3, 47
5. None of the above.

*** .explanation

There are N = 50 data points and C = 4 coefficients (including the intercept). Hence the missing degrees of freedom are 4 - 1 = 3 and 50 - 4 = 46.


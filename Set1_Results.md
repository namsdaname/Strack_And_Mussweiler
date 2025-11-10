Levene's Test for Homogeneity of Variance (center = median)
      Df F value Pr(>F)
group  2  0.6021 0.5596
      16             
      
      
 lag Autocorrelation D-W Statistic p-value
   1      0.01613765      1.959961   0.942
 Alternative hypothesis: rho != 0
 
 
 	Shapiro-Wilk normality test

data:  AOV(Set1$Z, Set1$H)$residuals
W = 0.44967, p-value = 1.853e-07

	One-way analysis of means

data:  Set1$Z and Set1$H
F = 0.63379, num df = 2, denom df = 16, p-value = 0.5434


      The ANOVA (formula: column1 ~ column2) suggests that:

  - The main effect of column2 is statistically not significant and medium (F(2, 16) =
0.63, p = 0.543; Eta2 = 0.07, 95% CI [0.00, 1.00])

Effect sizes were labelled following Field's (2013) recommendations.
      

The ANOVA (formula: column1 \~ column2) suggests that:

-   The main effect of column2 is statistically not significant and medium (F(2, 16) = 0.63, p = 0.543; Eta2 = 0.07, 95% CI [0.00, 1.00])

Effect sizes were labelled following Field's (2013) recommendations.


	Kruskal-Wallis rank sum test

data:  Set1$Z by Set1$H
Kruskal-Wallis chi-squared = 4.3887, df = 2, p-value = 0.1114
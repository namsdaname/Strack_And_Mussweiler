 lag Autocorrelation D-W Statistic p-value
   1       0.2450258      1.502144   0.204
 Alternative hypothesis: rho != 0
 
 Levene's Test for Homogeneity of Variance (center = median)
      Df F value Pr(>F)
group  2  1.5343 0.2425
      18             
      
Terms:
                   Set3$H Residuals
Sum of Squares   6.606606 13.393394
Deg. of Freedom         2        18

Residual standard error: 0.8625992

The ANOVA (formula: Set3$Z ~ Set3$H) suggests that:

  - The main effect of Set3$H is statistically significant and large (F(2, 18) = 4.44, p
= 0.027; Eta2 = 0.33, 95% CI [0.03, 1.00])

	Kruskal-Wallis rank sum test

data:  Set3$Z by Set3$H
Kruskal-Wallis chi-squared = 11.15, df = 2, p-value = 0.003792
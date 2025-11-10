 lag Autocorrelation D-W Statistic p-value
   1    -0.005474418      1.940165   0.964
 Alternative hypothesis: rho != 0
 
 Levene's Test for Homogeneity of Variance (center = median)
      Df F value Pr(>F)
group  2  0.3587 0.7065
      11  
      
      
      Call:
   aov(formula = Set4$Z ~ Set4$L)

Terms:
                   Set4$L Residuals
Sum of Squares   0.621111 12.378889
Deg. of Freedom         2        11

Residual standard error: 1.060827
Estimated effects may be unbalanced

The ANOVA (formula: Set4$Z ~ Set4$L) suggests that:

  - The main effect of Set4$L is statistically not significant and small (F(2, 11) =
0.28, p = 0.764; Eta2 = 0.05, 95% CI [0.00, 1.00])

Effect sizes were labelled following Field's (2013) recommendations.


	Shapiro-Wilk normality test

data:  aov(Set4$Z ~ Set4$L)$residuals
W = 0.69686, p-value = 0.0003429

	Kruskal-Wallis rank sum test

data:  Set4$Z by Set4$L
Kruskal-Wallis chi-squared = 3.2968, df = 2, p-value = 0.1924

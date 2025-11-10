	Shapiro-Wilk normality test

data:  aov(Set2$Z ~ Set2$L)$residuals
W = 0.52631, p-value = 8.665e-07


	One-way analysis of means

data:  Set2$Z and Set2$L
F = 0.70684, num df = 2, denom df = 16, p-value = 0.508


The ANOVA (formula: column1 ~ column2) suggests that:

  - The main effect of column2 is statistically not significant and medium (F(2, 16) =
0.71, p = 0.508; Eta2 = 0.08, 95% CI [0.00, 1.00])

Effect sizes were labelled following Field's (2013) recommendations.

	Kruskal-Wallis rank sum test

data:  Set2$Z by Set2$L
Kruskal-Wallis chi-squared = 6.0232, df = 2, p-value = 0.04921

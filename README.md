## Objective

This code (*schoendfeld_vs_freedman.Rmd*) has the aim to shown the performance of **Freedman** and **Schoendfeld** formulas by simulation.

- Schoendfeld formula:

$E=\frac{4(Z_{\alpha/2}+Z_{\beta})^2}{\left(log(HR)\right)^2}$

- Freedman formula:

$E=\frac{(HR+1)^2(Z_{\alpha}+Z_{\beta})^2}{\left(HR-1\right)^2}$


The simulation parameters are the following:

- **Number of simulations**:10,000
- **Follow-up &Tau;**: 1
- **HRs tested**: from 0.05 to 0.95
- **Test**: Log-rank
- **Exponential distributions**:

$T_C \sim Exp(\lambda_C=1)$

$T_T \sim Exp(\lambda_T=HR)$

See *html* file to see the results.

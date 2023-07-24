# python_statistics

## Testes de verificação de aderência à Distribuição Normal 

- Shapiro-Wilk: scipy.stats.shapiro
- Anderson-Darling: scipy.stats.anderson
- Kolmogorov-Smirnov: scipy.stats.kstest
- D’Agostino’s K-squared test: scipy.stats.normaltest
- Lilliefors: statsmodels.stats.diagnostic.lilliefors
- Cramer-von Mises: scipy.stats.cramervonmises

### Referências

- Shapiro, S. S. & Wilk, M.B (1965). An analysis of variance test for normality (complete samples), Biometrika, Vol. 52, pp. 591-611.
- D’Agostino, R. B. (1971), “An omnibus test of normality for moderate and large sample size”, Biometrika, 58, 341–348
- D’Agostino, R. and Pearson, E. S. (1973), “Tests for departure from normality”, Biometrika, 60, 613–622.
- Anderson, T. W.; Darling, D. A. (1952). “Asymptotic theory of certain “goodness-of-fit” criteria based on stochastic processes”, Annals of Mathematical Statistics, 23, 193–212.
- Anderson, T.W.; Darling, D.A. (1954). “A Test of Goodness-of-Fit”, Journal of the American Statistical Association, 49, 765–769.
- Kolmogorov–Smirnov Test (2008). In: The Concise Encyclopedia of Statistics. Springer, New York, NY.
- Lilliefors, Hubert W. (1967–06–01). “On the Kolmogorov-Smirnov Test for Normality with Mean and Variance Unknown”. Journal of the American Statistical Association. 62 (318): 399–402.

## Testes paramétricos e não paramétricos

Os termos paramétrico e não-paramétrico referem-se à média e ao desvio-padrão, que são os parâmetros que definem as populações que apresentam distribuição normal. 
Quando um pesquisador utiliza:

- testes paramétricos: supõe-se que a distribuição de seus dados experimentais seja normal.
- testes não-paramétricos: supõe-se que a distribuição de seus dados experimentais não seja normal.

Na dúvida quanto a essa informação, nada impede que ele opte pelo uso da estatística não-paramétrica. O que ele não pode fazer, de modo algum, é argumentar em termos de desvios ou erros padrões, embora possa perfeitamente fazê-lo pura e simplesmente em termos de médias.

Os detalhes que devem orientar a escolha do teste são:

- a existência ou não de vinculação entre dois ou mais fatores de variação;
- o número de componentes da amostra, que vão ser comparados.

<table border="1">
<tr>
    <th colspan="4">Testes estatísticos</th>
</tr>
<tr>
    <th colspan="2">Paramétricos</th>
    <th colspan="2">Não-paramétricos</th>
</tr>
<tr>
    <td>Independentes</td>
    <td>Vinculados</td>
    <td>Independentes</td>
    <td>Vinculados</td>
</tr>
<tr>
    <td>2 amostras</td>
    <td>2 amostras</td>
    <td>2 amostras</td>
    <td>2 amostras</td>
 </tr>
 <tr>
    <td>Teste t (Student)</td>
    <td>Teste t (Student)</td>
    <td>Mann-Whitney</td>
    <td>Wilcoxon</td>
  </tr>
  <tr>
    <td>Mais de duas</td>
    <td>Mais de duas</td>
    <td>Mais de duas</td>
    <td>Mais de duas</td>
  </tr>
  <tr>
    <td>Análise de variância</td>
    <td>Análise de variância</td>
    <td>Kruskal-Wallis</td>
    <td>Cochran</td>
  </tr>
</table>


# python_statistics

## Testes de normalidade

- Shapiro-Wilk
- Anderson-Darling
- Kolmogorov-Smirnov

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
    <td>Wilcoxon<br/>T. dos sinais<br/>Mac Nemar<br/>Binomial</td>
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


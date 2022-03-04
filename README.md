# dashboard_vendas_PowerBI
Dashboard realizado no desafio do curso Microsoft Power BI Para Data Science, Versão 2.0 da data science academy.


Projeto realizado utilizando o dataset de vendas de uma empresa que possui diversas lojas de vendas de eletrodomésticos na região Sudeste, na Bahia e no estado do Paraná.
O Projeto foi realizado utilizando a linguagem M e DAX no na própria ferramenta do Power BI, linguagens que foram usadas para que a modelagem do dataset fosse realizada.
Exemplos de utilização de modelagem:

1) Foi criada uma coluna de margem de lucro que foi explanada no relatório final. Essa coluna foi criada através da seguinte função: 
margem_de_lucro = 1 - (DIVIDE([Preço Custo], [Valor de Venda], 0)).

2) Foi criada uma medida de média de vendas que também foi utilizada no relatório final através da seguinte fórmula DAX:
Media_vendas = AVERAGE(Custos[Valor de Venda])

Conclusões:
No problema de negócio foi solicitado a média de vendas, a margem de lucro, o valor de venda dos produtos x o preço de custo dos mesmos e o indicador chave de performance(meta de  margem de lucro). Pode-se ver no relatório final que todas as demandas foram solucionadas com clareza e o setor de negócios da empresa pode utilizar o dashboard para futuras análises de vendas e custos.

Insghts:

1) No gráfico de média de vendas do mês de março, foi utilizado um gráfico de linhas, e nele, se pode observar que existe uma grande oscilação nas vendas durante o período, com o auge de vendas sendo atingido entre os dias 5 e 10.

2) No gráfico de margem de lucro por produto, percebe-se que o produto mais vendido é o de código BX103, então, a empresa pode investir mais na venda desse produto.

3) No gráfico de dispersão "Valor de vendas x preço de custo", pode-se observar que, quanto maior o preço de custo, maior o valor de venda, seguindo uma lógica clara.

4) Na demonstração da meta da margem de lucro, pode-se perceber que as vendas estão 4.72% abaixo da meta que, como é demonstrado na visualização, é de 53,01%.

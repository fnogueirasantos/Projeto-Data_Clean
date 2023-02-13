
# Tratando e Analisando Dados Fiscais e Contábeis

Problema de negócio: Hoje a Farmacia XX recebe seus dados fiscais e contábeis da contabilidade via planilha extraída do sistema usado para registros de lançamentos. 

Fomos acionados pelo gerente de contraladoria da Farmacia para criar um processo de automatização destes dados e entregar um relatório análitico do faturamento fiscal, dos impostos (ISS e Cofins) e a construção de uma DRE(Demonstração do resultado do exercício) com os dados contábeis.

## Insigths e Conclusões

Resultado Contábil

- A Empresa praticamente manteve sua receita líquida de um ano para o outro.
- Houve uma redução de 51% nos custos dos produtos o que impactou diretamente o lucro bruto com um aumento de 58.08% em relação ao período anterior.
- As contas relacionadas a despesas com pessoal reduziu em 25.95%.
- A conta de despesas gerais quase dobrou o seu valor d eum período para o outro, ao plotar um gráfico para identificar o motivo, foi visualizado o gasto elevado em 2022 com prestadores de serviços.

O objetivo do projeto foi demonstrar todo processo de geração de relatórios e insights de negócio a partir de 2 planilhas enviadas pela contabilidade da Farmacia XX.

Após o script os dados ficaram limpos, tratados e organizados. Foi possível realizar uma exploração e identificar alguns insghts de negócio e concluímos nosso objetivo de facilitar a vida do gerente de controladoria na análise dos dados fiscais e contábeis da empresa.

É possível realizar ainda mais automatizações, como por exemplo fazer a ingestão em um banco de dados usando SQL Alchemy. Mas isso ficará para uma nova versão do projeto.





## Instalação

Instale os pacotes abaixo para rodar o notebook:

```bash
  !pip install datetime
  !pip install warnings
```
    

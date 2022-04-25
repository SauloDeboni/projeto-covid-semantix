# Projeto Covid Semantix
Projeto Final do curso de Big Data Engineer da Semantix Academy<br/>
A documentação do projeto está no Notebook **projeto-covid**

****

### Sumário do Projeto
1. Envio de dados para o HDFS<br/>
Os dados originais estão salvos na pasta **data**.

2. Otimização dos dados para uma Tabela Hive<br/>
**Observação:** Não foi possível fazer o particionamento por municipio por falta de memória do computador. Portanto, para poder seguir com o projeto, o particionamento foi feito com estado.

3. Criar três visualizações pelo Spark com os dados do HDFS<br/>
3.1 **Visualização 01:** Os estados com maior número de casos X Total de óbitos<br/>
3.2 **Visualização 02:** Cidades pequenas (até 50 mil habitantes) com maior número de óbitos<br/>
3.3 **Visualização 03:** Épocas do ano (mês/ano) com maior número de novos casos<br/>

7. Criar a visualização pelo Spark dos dados do HDFS<br/>
Síntese de casos, óbitos, incidência e mortalidade

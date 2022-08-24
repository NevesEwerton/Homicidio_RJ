# Homicidio_RJ

O presente projeto tem como objetivo analisar o perfil das vítimas de homicídio nas cidades com maior número de assassinatos (números absolutos) do Estado do Rio de Janeiro. Para tal, fiz uso dos dados do Sistema de Informações de Mortalidade (SIM). Os dados foram baixados direto do datalake do Base dos Dados (BD). Foi necessário fazer alguns tratamentos nos microdados do SIM para conseguir fazer a análise do perfil das vítimas. Foi dada ênfase a questões como gênero, raça, idade etc. Foram analisadas apenas as cidades com maior número (absolutos) de assassinatos, pois do Estado do Rio de Janeiro tem como característica a concentração de alguns dados na região metropolitana do estado. 

## Bibliotecas 

As bibliotecas abaixo foram utilizadas para tratar os microdados do SIM e gerar as visualizações do projeto:

* `pandas`(manipulação e visualização de dados);
* `basedosdados`(coleta de dados);
* `numpy`(manipulação de dados);
* `matplotlib.pyplot`(visualização de dados);
* `seaborn`(visualização de dados estatísticos);


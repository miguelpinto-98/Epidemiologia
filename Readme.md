# Epidemiologia Covid-19
 
 Este trabalho foi realizado no âmbito da cadeira de SIG (Sistemas de Informação Geográfica), tendo como objetivo a análise epidemiologica do Covid-19.

Este Github está dividido em várias partes, três das quais são de análise global (uma a partir de  gráficos e análise estatística e as outras duas a partir de análise de mapas (quer por País quer por Continente) ), uma outra parte é relativa à previsão da Pandemia na China, sendo que ainda tem uma secção para o exercício proposto no [GitHub Jgrocha](https://github.com/jgrocha/covid-pt/tree/master/Jupyter).

## [Estatística_Mundial.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Estatística_Mundial.ipynb) 
* Para este Jupyter foram utilizados dados disponibilizados quer pelo [DataHub](https://datahub.io/core/covid-19) quer também pelo
[COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

* Gráficos com estatisticas mundias com a evolução da pandemia, 2 exemplos :
<img src="figuras/EVpandemia.png" width="600" height="600">
<img src="figuras/graf.EVconfirmados.png" width="600" height="600">
<img src="figuras/graf.EVinfetados.png" width="600" height="600">
<img src="figuras/pieCountries.png">


## [Dados_Por_País.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Dados_Por_País.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19) quer também pelo
[Natural Earth](https://www.naturalearthdata.com/)

* Vários mapas criados a partir do PyQgis com a evolução da pandemia por País a nível mundial  sendo os mais relevantes:

### Recuperados por País
<img src="figuras/Mundo_Recuperados.png">

### Confirmados por País
<img src="figuras/Mundo_Confirmados.png">



## [Dados_Por_Continente.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Dados_Por_Continente.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) quer também pelo
[Arcgis](https://www.arcgis.com/home/item.html?id=5cf4f223c4a642eb9aa7ae1216a04372)

* Vários mapas criados a partir do PyQgis com a evolução da pandemia por continente, sendo o mais relevante o seguinte (mapa mundo de recuperados):

### Confirmados por Continente

<img src="figuras/ECDC_confirmados.png" >

### Mortes por Continente
<img src="figuras/ECDC_Mortes.png">


## [Previsão Pandemia na China](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Previs%C3%A3o%20Pandemia%20na%20China/Previs%C3%A3o.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

* Foi feita uma previsão para o número de casos totais da China com base numa função logística, para os 40 dias seguintes:

<img src="figuras/ChinaTotal.png" >

* Também foi feita uma previsão para o número de novos casos diários da China com base numa função gaussiana, para os 40 dias seguintes:

<img src="figuras/ChinaDiario.png">

## Autor
* **Miguel Pinto**  - [miguelpinto-98](https://github.com/miguelpinto-98)

Ver também a lista de  [contributors](https://github.com/miguelpinto-98/Epidemiologia/contributors) que participaram no projeto.

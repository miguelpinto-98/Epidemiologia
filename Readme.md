# Epidemiologia Covid-19
 
 Este trabalho foi realizado no âmbito da cadeira de SIG (Sistemas de Informação Geográfica), tendo como objetivo a análise epidemiologica do Covid-19.

Este Github está dividido em 3 partes, duas partes de análise global, uma partir de  gráficos outra a partir de mapas e uma terceira para a resolução de exercicios propostos no  [GitHub Jgrocha](https://github.com/jgrocha/covid-pt/tree/master/Jupyter).

## [Estatística_Mundial.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Estatística_Mundial.ipynb) 
* Para este Jupyter foram utilizados dados disponibilizados quer pelo [DataHub](https://datahub.io/core/covid-19) quer também pelo
[COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

* Gráficos com estatisticas mundias com a evolução da pandemia, 2 exemplos :
<img src="figuras/EVpandemia.png" width="800" height="800">
<img src="figuras/pieCountries.png" width="800" height="800">


## [Dados_Por_País.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Dados_Por_País.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19) quer também pelo
[Natural Earth](https://www.naturalearthdata.com/)

* Vários mapas criados a partir do PyQgis com a evolução da pandemia por País a nível mundial  sendo os mais relevantes:

![Mapa Mundo Recuperados](figuras/Mundo_Recuperados.png){:height="50%" width="50%"}

![Mapa Mundo Recuperados](figuras/Mundo_Confirmados.png  | width=75)



## [Dados_Por_Continente.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Dados_Por_Continente.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) quer também pelo
[Arcgis](https://www.arcgis.com/home/item.html?id=5cf4f223c4a642eb9aa7ae1216a04372)

* Vários mapas criados a partir do PyQgis com a evolução da pandemia por continente, sendo o mais relevante o seguinte (mapa mundo de recuperados):
![Mapa Mundo Confirmados](figuras/ECDC_confirmados.png)

## [Previsão Pandemia na China/Previsão.ipynb](https://github.com/miguelpinto-98/Epidemiologia/blob/master/Previs%C3%A3o%20Pandemia%20na%20China/Previs%C3%A3o.ipynb) 

* Para este Jupyter foram utilizados dados disponibilizados quer pelo [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

* Foi feita uma previsão para o número de casos totais da China com base numa função logística, para os 40 dias seguintes:

![Foto1](figuras/ChinaTotal.png)

* Também foi feita uma previsão para o número de novos casos diarios da China com base numa função gaussiana, para os 40 dias seguintes:

![Foto](figuras/ChinaDiario.png)
## Autores

* **Miguel Pinto**  - [miguelpinto-98](https://github.com/miguelpinto-98)

Ver também a lista de  [contributors](https://github.com/miguelpinto-98/Epidemiologia/contributors) que participaram no projeto.

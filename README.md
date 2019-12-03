# Workshop de Python aplicado ao Censo 

Este material corresponde ao workshop introdutório de Python realizado no dia 29/11/2019 na FACE- UFMG para 
alunos do curso de estatistica e demográfia. O curso é uma iniciativa do CEDEPLAR/UFMG e faz parte da série de
cursos Desvendando o Método.

Este workshop apresentou noções básicas do software Python. O Python é uma linguagem de programação,
criada por Guido van Rossum em 1991 para produzir códigos de maneira simples e que executem de forma rápida.
O Python apresenta uma infinidade de ferramentas que são amplamente utilizadas para análise de dados,
aplicação de técnicas de Machine Learning, Inteligência Artificial, entre outras. No workshop foram apresentados os microdados
do Censo Demográfico de 2010 e algumas ferramentas úteis do python para manipulação e análise dos dados.


### Professoras :

Marina Amorim - [Link para Github](https://github.com/MarinaAmorim)  
Marina Tomás - [Link para Github](https://github.com/marinattomas)

## Materiais do curso

## 1) Como instalar o Python

O curso propoe a utilização do python através do Jupyter notebook. O Jupyter Notebook é uma aplicação de código aberto que
permite criar e compartilhar documentos com código dinâmico, visualizações de gráficos, limpeza de dados e 
até textos explicatórios. Esta apresentação apresneta explicações sobre o Python, Anaconda e Jupyter e as devidas instalações.

[Clique aqui para ver o manual de instalação](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/Python%20-%20Instala%C3%A7%C3%A3o%20.pdfs)

## 2)  Manual de introdução Python

A parte da manhã focou em introduzir alguns conceitos básicos de Python que facilitam o entendimento do script para 
microdados do censo. O material abaixo é um manual inicial de python e possui alguns links para orientar a utilização do python após o workshop. 

[Link para o manual de python](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/Python%20-%20Instala%C3%A7%C3%A3o%20.pdfs)  
[Link para a atividade 1 - Iteração no Python](https://github.com/marinattomas/Curso-de-Python-aplicado-ao-Censo/blob/master/Itera%C3%A7%C3%A3o%20no%20Python.ipynb)  
Atividade 2- Iris - *Em breve*

## 3)Como baixar os microdados

As instruções para baixar os microdados se encontram na apresentação *Microdados censo IBGE*. Para que o script rode 
corretamente é necessário abrir o notebook em um diretório que contenha a estrutura de pastas como explicadas neste arquivo, que 
são as pastas amostra repositório, amostras trabalho e layouts. Os links para este arquivo se encontra abaixo:

[Link para Manual - Microdados censo IBGE](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/Microdados%20IBGE%20-%20Censos%20Demogr%C3%A1fico.pdf)  

## 3) Script para abrir e manipular microdados

O script abaixo foi feito para ensinar como abrir e manipular microdados do CENSO no Python. Durante o curso rodamos apenas 
o estado do Acre e Rondonia mas o mesmo script pode ser aplicado para mais estados, basta adicionar os arquivos na estrutura de pastas correta. 
É importante ressaltar que esse script tinha como objetivo ensinar python para uma turma iniciante, se o objetivo for utilizar o Python 
para trabalhar com os dados de todo o CENSO pode ser que utilizar pandas não seja uma boa escolha, neste caso recomendamos ou filtrar
os dados de interesse antes de concatenar ou utilizar outras estratégias como Dask ou Pyspark.

[Link para o script de microdados](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/microdata_censo.ipynb)

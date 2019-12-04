# Workshop de Python aplicado ao Censo 

Este material corresponde ao workshop introdutório de Python realizado no dia 29/11/2019 na FACE- UFMG para 
alunos do curso de estatistica e demográfia. O curso foi um convite do professor Gilvan Guedes que acompanhou o Workshop virtualmente e é uma iniciativa do CEDEPLAR/UFMG como parte da série de cursos Desvendando o Método . 

Este workshop apresentou noções básicas do software Python. O Python é uma linguagem de programação,
criada por Guido van Rossum em 1991 para produzir códigos de maneira simples e que executem de forma rápida.
O Python apresenta uma infinidade de ferramentas que são amplamente utilizadas para análise de dados,
aplicação de técnicas de Machine Learning, Inteligência Artificial, entre outras. No workshop foram apresentados os microdados
do Censo Demográfico de 2010 e algumas ferramentas úteis do python para manipulação e análise dos dados.


### Professoras :

Marina Amorim - Mestranda em estatistica - UFMG - [Link para Github](https://github.com/MarinaAmorim)  
Marina Tomás - Mestranda em sociologia -UFMG // Observatório INCITE - [Link para Github](https://github.com/marinattomas)


![Foto curso](https://github.com/marinattomas/Curso-de-Python-aplicado-ao-Censo/blob/master/Foto-Workshop.jpeg)
Foto ao final do workshop

## Materiais do curso

## 1) Como instalar o Python e usar Jupyter

O curso propoe a utilização do python através do Jupyter notebook. O Jupyter Notebook é uma aplicação de código aberto que
permite criar e compartilhar documentos com código dinâmico, visualizações de gráficos, limpeza de dados e 
até textos explicatórios. Esta apresentação apresenta explicações sobre como instalar o Python, Anaconda e também uma introdução sobre o uso do jupyter e sua instalação.

[Clique aqui para ver o manual de instalação](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/Python%20-%20Instala%C3%A7%C3%A3o%20.pdfs)

## 2)  Manual de introdução Python

A parte da manhã focou em introduzir alguns conceitos básicos de Python que facilitam o entendimento do script para 
microdados do censo. O material abaixo é um manual inicial de python e possui alguns links para orientar a utilização do python após o workshop. 

**[Link para o manual de python](https://github.com/MarinaAmorim/Curso-de-Python-aplicado-ao-Censo/blob/master/Curso%20de%20Python%20-%20Introdu%C3%A7%C3%A3o.pdf)**
  
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
os dados de interesse antes de concatenar ou utilizar outras estratégias como Dask ou Pyspark. Também ressaltamos que as análises feitas não necessáriamente são as mais adequadas para estes dados ao se considerar a base teórica, o que queriamos mostrar era principalmente
a  ferramenta por isso não focamos em interpretações dos dados ou em escolher as variáveis mais significativas.

[Link para o script de microdados](https://github.com/marinattomas/Curso-de-Python-aplicado-ao-Censo/blob/master/Notebook_Python_Curso.ipynb)

# Quer aprender mais sobre Python?- Alguns liks uteis
*em produção*

No final do manual do curso colocamos alguns links, além disso colocaremos aqui nesta lista materiais interessantes para auxiliar no estudo do Python e também para quem se interesse na sua aplicação em ciência de dados. A lista ainda está em produção e será atualizada em breve:

-[Workshop prático de Dados](https://github.com/juditecypreste/Aprenda-Python-analisando-os-tuites-do-nosso-presidente) - Sugestão do Colaboradados 

- [Curso de Python Básico Solyd](https://solyd.com.br/treinamentos/python-basico) - O curso da Solyd é gratuito e muito bom, ensina os básicos da linguagem e fornece certificado.

- [Curso data science academy](https://www.datascienceacademy.com.br/course?courseid=python-fundamentos)- O data science academy fornece um curso de python básico para data science usando jupyter notebook.

- [Como iniciar em data science](http://colaboradados.com.br/blogposts/para-iniciar-em-data-science.html) - Post  do Colaboradados bem completo, tem informações sobre Python mas também sobre outros aspectos relacionados a data science. 

- [Guia do Cientista de Dados das Galáxias](https://github.com/PizzaDeDados/datascience-pizza) - Um guia do podcast Pizzza de Dados com várias informações sobre datascience 

- [Onde encontrar conjunto de dados](https://medium.com/rladiesbh/19-lugares-para-encontrar-conjuntos-de-dados-gratuitos-para-projetos-de-ci%C3%AAncia-de-dados-4390943d860d)- Texto do Rladies BH que apresenta onde achar conjuntos de dados para explorar.

- [Python x R](https://www.youtube.com/watch?v=W3J7EiSXAO0) - Video do canal Peixe Babel sobre Python vs R

# <p align="center"> <b>  Case Técnico CSGO</b>

##  Sobre o projeto: </br> </br> 

A primeira parte do case contém dados de partidas de Counter Strike, assim como dados dos jogadores. E o objetivo é consumir os dados de um banco MySql,
fazer os devidos tratamentos e disponibilizados a parti de uma regra de negócio definida por questão.
A segunda parte do case tem como objetivo fazer uma chamada a API do pokemon, onde contém dados dos pokemons e suas respectivas gerações, assim como
tipo, ataque e defesa hp.

  
A lógica usada para resolução do case:
    - O entendimento do problema foi o pontapé inicial, lendo as documentações disponibilizadas e também fazendo o entendimento de qual tipo de
    dados estaria lidando.

<b> 1- Entender o problema </b></br>
  
<b> 2- Consumo dos dados</b> </br>
     
    -Usando python para fazer uma consulta dentro de um banco MySql e retornar os dados em formato dataframe 
    -Ler e entender a documentação para o consumo da API (pokemon), montar uma função que faça o consumo e retorne o que foi pedido
    
<b> 3 -Manipulação de dados</b> <br>

     -Para atender a várias regras de negócio, foi necessário usar da linguagem SQL para criação de 
     novas métricas que não eram disponibilizadas no bando de dados
     - Também foi usada a linguagem Python para manipulação de tratamento de dados no consumo a API
     
<b> 4 - DataViz </b> <br>
     
     -Para a parte de visualização, foi disponibilizado um exemplo usando a biblioteca Plotly(Python), mas a ideia inicial seria criar um código em 
     Python para fazer o consumo desses dados e retonar um dashboard interativo usando o streamlit.
     
   
# <p align="center"> <b> Considerações Finais</b> 
   Devido ao tempo, nem todas as questões foram terminadas da maneira que eu gostaria, com muito mais detalhe e podendo disponibilizar de maneira mais 
   acessível ao usuário final. Mas de qualquer forma, estou a disposição para tirar possíveis dúvidas.

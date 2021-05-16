# House-Rocket

***Disclaimer: O Contexto a seguir, é completamente fictício, a empresa, o contexto, o CEO, as perguntas de negócio existem somente na minha imaginação.***
<p align="center">
  <img width="460" src="Imagem1.jpg">
</p>

## Contexto do Desafio

A ***House Rocket*** é uma plataforma digital que tem como modelo de negócio, a compra e a venda de imóveis usando tecnologia.

Você é um Data Scientist contratado pela empresa para ajudar a encontrar as melhores oportunidades de negócio no mercado de imóveis. O CEO da House Rocket gostaria de maximizar a receita da empresa encontrando boas oportunidades de negócio.

Sua principal estratégia é comprar boas casas em ótimas localizações com preços baixos e depois revendê-las posteriormente à preços mais altos. Quanto maior a diferença entre a compra e a venda, maior o lucro da empresa e portanto maior sua receita.

Entretanto, as casas possuem muitos atributos que as tornam mais ou menos atrativas aos compradores e vendedores e a localização e o período do ano também podem influenciar os preços.

Portanto, seu trabalho como Data Scientist é responder as seguinte perguntas:

1. **Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?**
2. **Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?**
3. **A House Rocket deveria fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças? Qual o incremento no preço dado por cada opção de reforma?**

## **Os Dados do Desafio**

O conjunto de dados que representam o contexto está disponível na plataforma do Kaggle.
Esse é o link: https://www.kaggle.com/harlfoxem/housesalesprediction

Esse conjunto de dados contém casas vendidas entre Maio de 2014 e Maio de 2015. Você usará esses dados para desenvolver sua solução.

## **Roteiro Sugerido para a Resolução.**
Esse é o roteiro de resolução do desafio que eu sugiro

1. **Identificar a causa raíz.**
   <ul>
       <li>Porque o CEO fez essas perguntas? Se você fosse ele, porque você perguntaria isso? Quer aumentar receita? A empresa está indo bem?
         Anote essas causas.</li>
    </ul>
2. **Coletando os dados ( Os dados estão no link acima )**

3. **Aplique uma limpeza nos dados.**
  <ul>
    <li>Entenda as variáveis disponíveis, possíveis valores faltantes, faça uma estatística descritiva para entender as características dos dados.</li>
  </ul>
  
4. **Levantando Hipóteses sobre o Comportamento do Negócio.**
    <ul>
        <li>Casas com garagens são mais caras? Porque?</li>
        <li>Casas com muitos quartos são mais caras? Porque? A partir de quantos quartos o preço aumenta? Qual o incremento de preço por cada quarto adicionado?</li>
        <li>As casas mais caras estão no centro? Qual a região? Existe alguma coisa na região que tem correlação com valor de venda da casa? Shoppings? Montanhas? Pessoas                   Famosas?</li>  
    </ul>
  
5. **Análise Exploratória de Dados.**

    <ul>
      <li>Quais hipóteses são falsas e quais são verdadeiras?</li>
      <li>Quais as correlações entre as variáveis e a variável resposta?</li>
    </ul>
  
6. **Os Insights que eu encontrei.**
7. **Escrevendo as possíveis soluções para o problema do CEO.**

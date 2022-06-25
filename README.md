# House Rocket

Esse é um desafio proposto pelo Meigarom do blog https://sejaumdatascientist.com/ e consiste da seguinte situação:

A House Rocket é uma plataforma digital que tem como modelo de negócio, a compra e a venda de imóveis usando tecnologia.

Você é um Data Scientist contratado pela empresa para ajudar a encontrar as melhores oportunidades de negócio no mercado de imóveis. O CEO da House Rocket gostaria de maximizar a receita da empresa encontrando boas oportunidades de negócio.

Sua principal estratégia é comprar boas casas em ótimas localizações com preços baixos e depois revendê-las posteriormente à preços mais altos. Quanto maior a diferença entre a compra e a venda, maior o lucro da empresa e portanto maior sua receita.

Entretanto, as casas possuem muitos atributos que as tornam mais ou menos atrativas aos compradores e vendedores e a localização e o período do ano também podem influenciar os preços.

Portanto, seu trabalho como Data Scientist é responder as seguinte perguntas:

1. Quais casas o CEO da House Rocket deveria comprar?
2. Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?
3. A House Rocket deveria fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças? Qual o incremento no preço dado por cada opção de reforma?

Considerando que todas as casas estão a venda e podem ser reformadas, algumas hipóteses foram listadas para serem validadas:

    H0: Imóveis que possuem vista para água são 30% mais caros, na média; 
    H1: Imóveis que possuem vista 3 ou 4 são 20% mais caros, na média;
    H2: Imóveis com data de construção menor que 1955, são 50% mais baratos, na média; 
    H3: Imóveis sem porão possuem sqrt_lot 50% maiores do que com porão; 
    H4: O crescimento do preço dos imóveis YoY ( Year over Year ) é de 10%; 
    H5: Imóveis com 3 banheiros tem um crescimento MoM ( Month over Month ) de 15%; 
    H6: Imóveis anunciados no verão são 10% mais caros, na média;
    H7: Imóveis reformados são 20% mais caros, na mesma região e na média;
    H8: Há uma alta correlação entre sqft_living e price;
    H9: A variação entre o 'grade' é de 20%, na média.

Após a validação das hipóteses, foi considerado a compra de imóveis com as seguintes features:
- Em boas condições;
- Abaixo da mediana de preço por zipcode;
- Abaixo da mediana de preço por view;
- Abaixo do preço esperado por tamanho do imóvel.

Em caso de compra dos imóveis recomendados, o total de gasto será de \\$460.505.622.

Caso todos os imóveis sejam vendidos pelo preço recomendado, a receita será de \\$556.726.432. Logo, um lucro de \\$96.220.810.

Foi constatado que a qualidade do material ('grade') da casa impacta diretamente no preço. Dessa forma, caso os imóveis comprados sofram uma reforma para revenda, a receita será de \\$750.772.725. Logo, um lucro potencial de \\$244.216.541, considerando o custo de reforma em 10% do valor de compra do imóvel.

<a href="https://app.powerbi.com/view?r=eyJrIjoiYjUzZTgyNTYtYWJmNi00YjFjLTlhN2EtYTA1NmUyZjg0Yzg0IiwidCI6IjY5ZGM3ZWRlLWM1MzAtNDIzZS1iOGFhLWViZmJlNTdlYWMwOSJ9">Link para Power BI</a>

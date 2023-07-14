# **Iowa Liquor - Análise Exploratória de Dados**

Em 1920 foi instituida a lei seca nos Estados Unidos, onde era proibida a fabricação, importação, venda ou transporte de bebidas alcoólicas dentro do país, ou de países sujeitos a sua jurisdição. O objetivo primordial dessa lei era o combate à pobreza e violência. Passados 13 anos a lei foi revogada, pois não gerou os resultados esperados.

Esse evento ficou marcado como um símbolo da relação dos Estados Unidos com o consumo de álcool. Segundo o CDC (Center for Disease Control and Prevention), [um em cada seis adultos faz consumo execissivo de álcool no país](https://www.cdc.gov/alcohol/fact-sheets/binge-drinking.htm). Esse dado demonstra um grave problema de saúde que afeta, principalmente, a população de jovens adultos (18 à 34 anos). Além disso, demonstra-se, como um mercado lucrativo e que necessita de atenção por parte de organizações, sobre o comportamento de consumo e quais ações devem ser tomadas contra o desenvolvimento da dependência em álcool.


## **Objetivo**

Realizar o desenvolvimento de um processo análitico de dados para o consumo de bebidas destiladas no Estado de Iowa. Para isso serão utilizadas perguntas norteadoras, que ajudarão a compreender melhor o consumo da bebida no decorrer dos anos.


## **Perguntas Norteadoras**

* Qual a quantidade total de lojas?
* Qual cidade possui mais lojas de bebidas licenciadas, que realizaram compras?
* Quais são os 10 produtos vendidos mais caros?
* Qual o fornecedor que mais vendeu em todo o período? E quais foram os fornecedores que mais venderam nos últimos 10 meses por mês?
* Qual a categoria mais vendida por volume total no período? E por quantidade de vendas realizadas?
* Qual o produto mais vendido por condado?
* Qual a loja que mais transacionou em volume monetário? E por quantidade de vendas? E por litros?
* Qual o produto que mais gerou receita para ABD no período? E qual o produto que mais possui margem de lucro?
* Parece haver sazionalidade na venda de bebidas? Algum mês do ano, no decorrer dos anos, possui mais destaque no volume vendido?
* Qual é o total vendido por ano?
* Qual foi o lucro por ano?
* Qual foi a evolução do comportamento de consumo?


## **Pré-requisitos**

Para realização dessa atividade será utilizado apenas Python 3.11.3 com as seguintes bibliotecas e versões:

* pandas    : 2.0.3
* numpy     : 1.24.4
* wget      : 3.2
* matplotlib: 3.7.1


## **Dados Utilizados**

O dataset que será utilizado na análise trata sobre as vendas de destilados do tipo liquor de classe "E" no estado de Iowa, fornecido pela plataforma de open data do estado de Iowa, e pode ser obtido [clicando aqui](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy). O período de tempo utilizado na análise está entre janeiro de 2012 e março de 2023.

O link direto para o Download do arquivo no formato utilizado na análise pode ser obtido [clicando aqui](https://data.iowa.gov/api/views/m3tr-qhgy/rows.csv?accessType=DOWNLOAD&bom=true&format=true). O script verifica se o arquivo já existe no diretório raiz do projeto, caso não, realiza o Download. No entanto, o processo pode demorar, devido ao tamanho do arquivo.


## **Descrição do Arquivo**

O arquivo utilizado trata sobre ordens de compras de bebidas alcóolicas no Estado de Iowa, destinado a ABD (Alcoholic Beverages Division). Nesse conjunto de dados há informações sobre data da compra, informações sobre o estabelecimento, tipo de bebida comprada, preço, informações sobre geolocalização e volume vendido.


## **Licença**

Os dados utilizados possuem a licença CC0, de dominio público, e foram fornecidos pelo Iowa Department of Commerce, Alcoholic Beverages Division.

[Iowa Liquor Sales](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy) by Iowa Department of Commerce, Alcoholic Beverages Division. The data is dedicated to the public domain under CC0.

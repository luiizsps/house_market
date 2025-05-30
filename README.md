# House Market

Imagine que você é um investidor imobiliário em King County, USA. Você deseja comprar um casa e revendê-la, obtendo o maior lucro possível. Neste projeto, iremos explorar os dados de vendas de casas na região, com o objetivo de responder às seguintes perguntas:
- Qual casa você deve comprar? Qual o custo estimado de compra?
- Quando a casa deve ser vendida? Por qual valor?
- Você fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças? Qual o incremento no preço dado por cada opção de reforma?

## Base de Dados
Nossa base de dados possui as seguintes informações:

| Coluna             | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| **id**             | Identificador único do imóvel.                                            |
| **date**           | Data do registro da venda do imóvel.                                      |
| **price**          | Preço de venda do imóvel (em dólares).                                    |
| **bedrooms**       | Número de quartos no imóvel.                                               |
| **bathrooms**      | Número de banheiros no imóvel (pode incluir frações, como 1.5).            |
| **sqft_living**    | Área interna útil da casa em pés quadrados (1 pé² ≈ 0,093 m²).             |
| **sqft_lot**       | Área total do terreno em pés quadrados.                                   |
| **floors**         | Número de andares da residência.                                           |
| **waterfront**     | Indica se o imóvel possui vista direta para a água (0 = não, 1 = sim).     |
| **view**           | Índice de qualidade da vista (escala de 0 a 4).                            |
| **condition**      | Índice de condição geral do imóvel (escala de 1 a 5).                      |
| **grade**          | Classificação da construção e design do imóvel (escala de 1 a 13).         |
| **sqft_above**     | Área construída acima do nível do solo, em pés quadrados.                  |
| **sqft_basement**  | Área do porão, em pés quadrados.                                           |
| **yr_built**       | Ano de construção do imóvel.                                               |
| **yr_renovated**   | Ano da última reforma (0 se nunca foi reformado).                         |
| **zipcode**        | Código postal da localização do imóvel.                                   |
| **lat**            | Latitude da localização geográfica do imóvel.                             |
| **long**           | Longitude da localização geográfica do imóvel.                            |
| **sqft_living15**  | Área interna média das 15 casas vizinhas mais próximas, em pés quadrados. |
| **sqft_lot15**     | Área média dos terrenos das 15 casas vizinhas mais próximas.              |
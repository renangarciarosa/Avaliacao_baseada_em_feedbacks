# Avaliação dos produtos baseada em feedbacks dos clientes

---

## Sobre o conjunto de dados

Conjunto de dados públicos de comércio eletrônico brasileiro feito por Olist

Dataset pode ser baixado aqui: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Este é um conjunto de dados público de e-commerce brasileiro de pedidos feitos na Olist Store. O conjunto de dados possui informações de 100 mil pedidos de 2016 a 2018 feitos em vários marketplaces no Brasil.

Suas funcionalidades permitem visualizar um pedido a partir de múltiplas dimensões: desde o status do pedido, preço, pagamento e desempenho do frete até a localização do cliente, atributos do produto e, finalmente, avaliações escritas pelos clientes. Também lançamos um conjunto de dados de geolocalização que relaciona CEPs brasileiros a coordenadas lat/lng.

Estes são dados comerciais reais, foram anonimizados e as referências às empresas e parceiros no texto da revisão foram substituídas pelos nomes das grandes casas de Game of Thrones.

## Contexto
Este conjunto de dados foi generosamente fornecido pela Olist, a maior loja de departamentos dos marketplaces brasileiros. A Olist conecta pequenas empresas de todo o Brasil a canais sem complicações e com um único contrato. Esses comerciantes podem vender seus produtos através da Olist Store e enviá-los diretamente aos clientes usando os parceiros de logística da Olist. Veja mais em: www.olist.com

Depois que um cliente compra o produto da Olist Store, um vendedor é notificado para atender esse pedido. Assim que o cliente recebe o produto, ou vence a data prevista de entrega, o cliente recebe uma pesquisa de satisfação por e-mail onde pode dar uma nota da experiência de compra e anotar alguns comentários.

## Informações relevantes

* Um pedido pode ter vários itens.
* Cada item pode ser atendido por um vendedor distinto.
* Todo o texto identificando lojas e parceiros foi substituído pelos nomes das grandes casas de Game of Thrones.


Aplicação de modelos de machine learning para predizer a avaliação dos produtos baseados no histórico de feedbacks dos clientes que já realizaram compras.

* LSTM - Rede Neural
* Regressão Logística
* SVM
* Random Forest
* XGBOOST

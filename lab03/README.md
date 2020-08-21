# Modelo para Apresentação do Lab03 - Model-View-Controller

## Tarefa 1

![tarefa1](/lab03/images/tarefa1.png)

## Tarefa 2

![tarefa2](/lab03/images/tarefa2.png)

1. O componente SelectProduct posta uma mensagem com tópico IProduct.
2. O component FindSupplier assina IProduct e posta IProductAgregate.
3. O component MakeOffer assina IProductAgregate e posta IOffer.
4. O component Auction assina IProduct e IOffer e posta IOfferAgregate.
5. O component ShowOffers assina IProduct e IOfferAgregate.

## Tarefa 3

[Aplicativo](/lab03/app/marketplace.aia)

### Tela 1 - nenhum produto selecionado

![Tela 1](/lab03/images/tela_1.jpg)

### Tela 2 - primeiro produto selecionado

![Tela 2](/lab03/images/tela_2.jpg)

### Tela 3 - segundo produto selecionado

![Tela 3](/lab03/images/tela_3.jpg)

### Tela 4 - compra de um dos produtos efetiva

![Tela 4](/lab03/images/tela_4.jpg)

### Tela 5 - diagrama de blocos do aplicativo

- **Home** 

![Home](/lab03/images/home.png)

- **Product Detail** 

![Product Detail 1](/lab03/images/product_detail.png)

![Product Detail 2](/lab03/images/product_detail1.png)

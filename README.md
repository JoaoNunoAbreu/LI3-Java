# LI3 2018/2019 - Java

## Grupo

* João Nuno Abreu
* Hugo Matias
* Jorge Vieira

## Validade de produtos (AB1234)

* 2 letras maiúsculas
* 4 dígitos entre 1000 e 9999

## Validade de clientes (A1234)

* 1 letra maiúscula
* 4 dígitos entre 1000 e 5000

## Validade de vendas (AB1234 123.12 123 N A1234 1 1)

* Código de produto (tem de estar na lista dos produtos válidos)
* Preço por unidade decimal entre 0.0 e 999.99
* Número de unidades compradas entre 1 e 200
* Compra normal ou promoção (N ou P)
* Código do cliente (tem de estar na lista dos clientes válidos)
* Mês da compra
* Filial entre 1 e 3

## Notas

* ~~Demora ainda muito tempo a validar (12 min) pois ainda se usa ArrayList<String> para guardar os produtos e clientes válidos.~~
* Falta fazer facturação e filial.
# Requisitos para ir a produção

Quando sua integração estiver pronta e quiser começar a receber pagamentos, complete o formulário para ir a produção através da [seção de Credenciais]([FAKER][CREDENTIALS][URL]).

## Por que é necessário realizar esse processo?

Com esse processo, se garante a segurança dos dados dos seus clientes, o cumprimento das normas e disposições legais de cada país e a melhor experiência de compra para as suas vendas.

[Conheça os termos e condições do Mercado Pago](https://www.mercadopago[FAKER][URL][DOMAIN]/ajuda/termos-e-condicoes_300).

## Use as bibliotecas oficiais e cuide da segurança dos dados

É importante que utilize a biblioteca MercadoPago.js como é fornecida pelo Mercado Pago. Não deve-se modificá-la nem armazená-la nos seus servidores. Assegure-se também de não incluir o atributo `name` ao criar um formulário de dados de cartão para prevenir que os dados cheguem aos seus servidores quando o cliente enviar o formulário.

Essas medidas permitem cuidar dos dados sensíveis, cumprir com os padrões de segurança requeridos e mantê-lo sempre atualizado.

## Tenha um certificado SSL

Para que seja seguro e que possa cuidar dos dados, é necessário que tenha um certificado SSL válido e que o formulário de pagamento seja disponibilizado em uma página HTTPS. Isso permite proteger as transações e os dados dos seus compradores. Durante os teste não é necessário tê-lo, mas é obrigatório para ir a produção.

## Seja transparente com as promoções e financiamentos

Deve-se comunicar claramento que as promoções são oferecidas pelo Mercado Pago. Pode-se [incluir um banner de meios de pagamento](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/banners/introduction/) ou [adicionar um link na seção de promoções](https://www.mercadopago.com.br/promocoes/). Também, deve-se informar os [custos de financiamento que se aplicam aos seus clientes](https://www.mercadopago.com.br/ajuda/Custos-de-parcelamento_322).

----[mla]----
> NOTE
>
> Nota
>
> Devido a Resolução [E 51/2017](https://www.boletinoficial.gob.ar/#!DetalleNormaBusquedaRapida/158269/20170125/resolucion%2051) da Secretería de Comércio Argentina, sobre preços transparentes, é necessário que cumpra com [exigencias adicionales](https://www.mercadopago.com.ar/developers/es/guides/localization/considerations-argentina/).
------------

## Disponibilize seus termos e condições

Disponibilize uma política de termos e condições e deixe claro que é responsável por todos os dados que sejam inserido no seu site.

---
### Próximos passos

> LEFT_BUTTON
>
> Teste sua integração
>
> Revise que esteja tudo bem com sua integração utilizando os usuários de teste.
>
> [Teste sua integração](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/guides/payments/api/testing/)

> RIGHT_BUTTON
>
> Referências de API
>
> Encontre toda a informação necessária para interagir com nossas APIs.
>
> [Referências de API](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/pt/reference/)
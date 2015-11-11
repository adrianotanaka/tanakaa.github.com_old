---
title: "Oracle Cloud, seria esse o futuro da computação?"
date: 2015-11-11 11:51:23 
categories: posts
layout: post
---

Tive a oportunidade de participar de um workshop sobre Oracle Cloud e pude ver algumas coisas interessantes que podem se tornar realidade no quesito banco de dados e também no suporte a aplicações, tudo utilizando a estrutura da própria Oracle.
Atualmente diversas empresas (as grandes principalmente) estão em uma corrida para ver quem vai dominar a nuvem que segundo especialista é um futuro inevitável: Todos em algum momento no futuro vão estar na nuvem.
No WorkShop foram apresentados diversas funcionalidades da nuvem da Oracle, listo as mais importantes abaixo:

[***Servidor Oracle Cloud localizado no Brasil***](https://www.oracle.com/corporate/pressrelease/data-center-brazil-062415.html)

Uma boa notícia para o Brasil e países da América Latina: a Oracle começou a oferecer em São Paulo um data center o que em teoria melhora alguns pontos no serviço oferecido (vou falar sobre isso daqui a pouco).

<img src="https://cdn.pbrd.co/images/23wFGBe0.png"/>

***Tudo na nuvem***

Uma das coisas que foi apresentado ontem foi que a Oracle vai passar a oferecer (sem data prevista ainda)  a capacidade de rodar diversas linguagens de programação, sem a necessidade de um servidor dedicado a isso, para java você já pode ver [aqui](https://cloud.oracle.com/en_US/java) como funciona.

Meu banco de dados na nuvem, e agora?
-

Um dos pontos que o instrutor focou foi o banco de dados na nuvem, existem diversas opções, você pode manter alguns serviços locais e outros na nuvem, várias versões de banco de dados e features disponíveis:
<img src="http://i.imgur.com/Sr9yYoC.png"/>
*Imagem retirada do site da Oracle*

Aqui que as coisas começam a ficar interessantes(pelo menos para quem mexe com banco), a Oracle realizar cobranças de duas formas:

**Mensal**
**Por consumo**

Ainda segundo o instrutor, em alguns casos(aqui entra o pessoal de vendas da Oracle), usar uma infraestrutura toda baseada em nuvem acaba saindo mais barato do que utilizar uma infra [On Premises](https://en.wikipedia.org/wiki/On-premises_software) além é claro de oferecer mais segurança, diminuir os custos e principalmente o tempo para uma nova implementação ou ajuste.

Colocando meu banco na nuvem
-

Um dos labs realizados foi o procedimento de implementar uma nova instância dentro da nuvem da Oracle.
Todo o processo de selecionar as configurações do servidor, tais como processador(a Oracle tem uma medida própria para isso) memória, disco e versão do banco de dados leva em torno de 1hora para single instânce e 2horas para um ambiente em cluster(infelizmente não tivemos tempo para de testar esse segundo cenário).

---
layout: default
title: "Monkey Nights - Hub de conteúdo Xamarin"
---
{% include JB/setup %}

### Bem vindo ao Monkey Hub!

Olá! O principal objetivo deste hub é responder à pergunta "Como aprender a desenvolver aplicativos moveis com C# e Xamarin?”, mas ele não fica só nisso. Com a ajuda da comunidade, você vai encontrar aqui não só uma lista de links para conteúdo, mas uma oportunidade de aprender, colaborar, conhecer pessoas e fazer parte comunidade Brasileira de desenvolvedores Xamarin.

Esperamos que você aproveite cada linha de conteúdo compartilhada aqui e que também colabore enviando um PR com aquele link que salvou a sua vida ;)

### Como funciona?

O objetivo é que a comunidade colabore com o hub, ou seja, todos podem enviar um PR para adicionar conteúdo.

Inicialmente dividimos o hub em cinco grupos de conteúdo: Xamarin, Xamarin.Android, Xamarin.iOS, Xamarin.Forms e Xamarin.Mac. Esta organização pode mudar conforme o conteúdo for crescendo, mas por hora acreditamos que é o suficiente para começarmos.

### Entendendo a Plataforma

Tem dúvidas sobre a plataforma Xamarin?

{% for post in site.data.posts %}
    {% if post.tags contains "index" %}
- [{{ post.name }}]({{post.url}})
    {% endif %}
{% endfor %}

### Autores e colaboradores

Aqui você encontra a lista de todas as pessoas que colaboram com este repositório, a ideia é que a pessoa com mais PR’s em um mês, ganhe um brinde da comunidade =)

Até o momento colaboraram com o hub:

- [@azchohfi](http://www.github.com/azchohfi)
- [@angelobelchior8](http://www.github.com/angelobelchior8)
- [@williamsrz](http://www.github.com/williamsrz)
- [@willsb](http://www.github.com/willsb)
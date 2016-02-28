---
layout: post
title: Desenvolvedor vs editor de código
description: Diferenças entre um desenvolvedor a um editor de código
category: Desenvolvimento
image: /assets/img/posts/flat-design.png
---

## Introdução
Olá malta, tudo bom?
Este é o meu primeiro post neste blog, e como já notaram, o tema é polêmico. Pois é, assim será daqui a diante.
Só para constar, este blog é de um desenvolvedor front-end, isto é, eu. Portanto, muitos dos assuntos que trataremos terá como foco, a  área web assim como o desenvolvimento de programas de computador.
Passarei dicas, minhas opiniões e pontos de vista.
Vale notar que tudo que escreverei será minha própria opinião de determinado assunto, então fique livre em criticar o meu ponto de vista.
Como aprendi na filosófia, todas ideias são válidas.

### Desenvolvedor

O desenvolvedor é aquele que estudou a lógica de desenvolvimento de determinada área ou linguagem, para quem queira entrar na área de desenvolvimento de apps, tanto por conta própria ou por causa da faculdade, primeiramente estudamos a lógica de programação, como chamam em algumas Universidades: Introdução a programação.

Então seguindo a lógica de desenvolvimento, o desenvolvedor procura por soluções para seu problema, isto é, ele raciocina em como pode resolver algo, criando teórias e experimentos.
Está página por exemplo, enquanto eu criava o template no jekyll, tive que testar o visual como ficaria.
Este visual eu já vejo em várias páginas baseadas no Material Design, porém já é padrão do framework [Material design lite](http://getmdl.io), enquanto que neste framework que estou usando, [Materialize](http://materializecss.com), não tem um template parecido para posts por padrão.
No meu primeiro experimento, copiei um template do Material design lite e fiz modificações de acordo com o meu visual, mas pensei, porque usar dois frameworks numa só página? Então quis apenas usar o mdl, mas seria forçado a ter que aprender a usar-lo, embora não era algo mal, todavia eu não estava sendo produtivo. Desisti da ideia.

Comecei a pensar como um desenvolvedor, entrei no meu arquivo scss, e escrevi: 
<pre>
    <code>
        .post-header {
            background-color: $primary-color-dark;
            background-size: cover;
            height: 200px;
            
            article.container {
                background: #fff;
            }
        }
    </code>
</pre>

Pronto! embora não estava perfeito mas pelo menos criei uma solução para meu problema, assim com o tempo posso melhorar o visual implementando mas alguns experimentos até chegar no visual que desejo.

### Considerações finais
Então como é realmente ou quem é o editor de código, conhecido no desenvolvimento de programa de computador como script kid.
Este será o assunto do próximo artigo, ou quer dizer a parte 2.

Até a próxima!
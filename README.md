## Unidade de medida REM

A unidade rem é uma medida relativa que se baseia no tamanho da fonte do elemento raiz (HTML) da página. Isso significa que o tamanho de um elemento em rem será proporcional ao tamanho da fonte definido para o elemento HTML.

Por exemplo, se o tamanho da fonte do elemento HTML for 16px e você definir o tamanho da fonte de um título como 2rem, o título terá 32px de altura (2 x 16px).

Essa unidade é muito útil para criar layouts responsivos, pois o tamanho dos elementos se ajusta automaticamente de acordo com as preferências do usuário, como o tamanho da fonte do navegador.

Link do w3school: https://www.w3schools.com/cssref/css_units.php
para conseguir o rem, é só dividir o valor em pixel por rem: 32/16 = 2rem

## Porcentagem

A porcentagem é uma forma de representar uma fração com denominador 100. Ela é muito útil para comparar partes de um todo, como quando queremos saber qual a porcentagem de alunos que passaram em uma prova, ou qual a porcentagem de desconto em uma compra.

## media query

Imagine que você está construindo uma casa. Você precisa de portas e janelas diferentes para cada cômodo, certo? Media Queries funcionam da mesma forma! Elas permitem que você defina estilos específicos para telas pequenas, médias e grandes, como se estivesse criando "cômodos" diferentes para o seu site.

Por exemplo, você pode usar Media Queries para:
Ajustar o tamanho das fontes: Em telas pequenas, o texto pode ficar muito pequeno para ler. Com Media Queries, você pode aumentar o tamanho da fonte para melhorar a legibilidade.
Mudar o layout: Em telas pequenas, o layout do seu site pode ficar muito apertado. Com Media Queries, você pode reorganizar os elementos para que eles se encaixem melhor na tela.
Ocultar elementos: Em telas pequenas, alguns elementos podem ser desnecessários. Com Media Queries, você pode ocultá-los para que o site fique mais limpo e fácil de navegar.

Para usar Media Queries, você precisa usar a sintaxe @media. Dentro da regra @media, você define uma condição que será verificada pelo navegador. Se a condição for verdadeira, os estilos dentro da regra serão aplicados.

Exemplo:

```css
@media (max-width: 768px) {
  /_ Estilos para telas com largura máxima de 768px _/ .container {
    width: 100%;
  }
  .image {
    width: 50%;
  }
}
```

Neste exemplo, os estilos dentro das chaves serão aplicados apenas se a largura da tela for menor ou igual a 768px.

### Seletores CSS

Há muitos tipos diferentes de seletor CSS que permitem apontar regras para elementos específicos em um documento HTML. 

Abaixo segue um exemplo os seletores CSS mais usados.
 ```
<!DOCTYPE html>
<html>

<head>
    <title> CSS seletores</title>
</head>

<body>
    <h1 id="top">Kitchen Garden Calendar</h1>
    <p id="introduction" Here you can read our handy guide about what to do when.</p>
    <h2>Spring</h2>
    <ul>
        <li>
            <a href="mulch.html">
                Srping mulch vegetable beds
            </a>
        </li>
        <li>
            <a href="potato.html">
                Plant out earlyn potatoes
            </a>
        </li>
        <li>
            <a href="tomato.html">
                Sow tomato seeds
            </a>
        </li>
        <li>
            <a href="beet.html">
                Sow beet seeds
            </a>
        </li>
        <li>
            <a href="zucchini.html">
                Sow zucchini seeds
            </a>
        </li>
        <li>
            <a href="rhubarb.html">
                Deadread rhubarb flowers
            </a>
        </li>
    </ul>
    <p class="note">
        this page was written by
        <a href="malito:ivy@example.org">
            ivy@example.org
        </a> for
        <a href="http://www.example.org">
            Example
        </a>
    </p>
    <p>
        <a href="#top">Top of page</a>
    </p>
</body>
</html>
```
Nesta página, há um arquivo HTML para demonstrar os elementos aos quais  esses seletores CSS seriam aplicados.

## Seletores

| SELETOR    | SIGNIFICADO | EXEMPLO  |
| ------ | ----------- | --------- |
| Seletor Universal  | Aplica-se em todos os elementos no documento        | * {}  seleciona todos elementos da página     |
| Seletor de texto  | Seleciona elemento pelo tipo       | h1. h2. h3 Seleciona os elementos ```<h1>``` ```<h2>``` e ```<h3>```         |
| Seletor de classe  | Seleciona um elemento cujo  atributo class tem o valor especificado depois do ponto      | .note {} Seleciona qualquer elemento cujo o atributo class tem o valor  note p.note {} Seleciona somente elementos <p> cujo atributo class tem o valor note.         |
| Seletor de ID  | Seleciona um elemento cujo atributo id tem o valor especificado após o símbolo de cerquilha ou jogo-da-velha       | #introduction {} Seleciona o elemento cujo atributo id tem o valor introduction         |
| Seletor de filho  | Seleciona um elemento que é filho direto de outro       | li>a {} Seleciona quaiquer elementos ```<a>```{} Seleciona quaisquer elementos ```<a>``` que são filhos de um elemento ```<li>``` (mas não outros elementos ```<a>``` na página)         |
| Seletor de Descendente  | Selecionaum elemento que é descendente de outro elemento especificado (e não apenas filho direto desse elemento)       | p  a {} Seleciona quaisquer elementos ```<a>``` que residem dentro de um elemento ```<p>```, mesmo se houver outros elementos aninhados entre eles.         |
| Seletor de irmão adjacente  | Seleciona um elemento que é o irmão próximo do outro       | h1+p {} Seleciona o primeiro elemento ```<p>``` depois de qualquer elemento ```<h1>``` (mas não de outros elementos ```<p>```)         |
| Seletor de irmão geral  | Seleciona um elemento que é um irmão de outro, embora ele não precise ser o elemento diretamente precedente       | h1~p     {} Se houvesse dois elementos ```<p>``` que fossem irmãos de um elemento ```<h1>```, essa regra se aplicaria aos dois.     |

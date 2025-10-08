# funcoesjs

Tutorial de Funções: Como criar funções em javascript e para que servem.

## DEFININDO FUNÇÃO

Funções são blocos de código utilizados para melhorar a estrutura do código, já que trechos repetitivos acabam o deixando desnecessariamente grande e pode atrapalhar, se tiver um código complexo.<br>
Todas as funções possuem parâmetro e corpo. Na criação de uma função, o parâmetro pode ou não ser especificado, vindo após o identificador e entre parênteses, e o corpo entre as chaves {}.
Exemplo: `function subtrair(valor1, valor2){
   return valor1 - valor2;
}`

## FUNÇÃO DECLARATIVA

Ao criar a função declarativa, inicia-se o código com a palavra-chave `function`, seguido pelo identificador, os parâmetros desejados e então o seu corpo com o retorno pretendido.

```
function somar(valor1, valor2){
  return valor1 + valor2;
}
```

Esta é uma função declarativa, ela pode ser chamada mesmo que esteja abaixo do código, pois ela não está definida como uma variável. É parecida com a característica do `var` de içamento, o `HOISTING`.

#### desvantagem

Pode deixar seu código confuso. E não são tão flexíveis.

## FUNÇÃO EXPRESSIVA

Para criar uma função expressiva, faz-se uso da função dentro de uma variável, para que seja de fato expressiva, que expresse a variável.
Segue uma sintaxe parecida com a `declaration`, mas é mais utilizada que a função declarativa.

```
let somar = function(valor1, valor2) {
  return valor1 + valor2;
};
```

Diferentemente da declarativa, ela necessita do `;` após o corpo, para que fique assim: `{};`, pois é uma expressão atribuída a uma variável e não uma declaração de fato.

## FUNÇÃO ARROW

É a função mais utilizada para ações curtas, pois ela é bem resumida estruturalmente.

```
let somar = (a, b) => a + b;
```

Só é preciso utilizar o `return` quando se usa as chaves, mas na maior parte das funções não será tão necessário o uso delas.

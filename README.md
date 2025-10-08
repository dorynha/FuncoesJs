# funcoesjs
Tutorial de Funções: Como criar funções em javascript e para que servem.
## DEFININDO FUNÇÃO

Funções são blocos de código utilizados para melhorar a estrutura do código, já que trechos repetitivos acabam o deixando  desnecessariamente grande e pode atrapalhar, se tiver um código complexo.<br>
Todas as funções possuem parâmetro, corpo e argumento. Na criação de uma função, o parâmetro pode ou não ser especificado, vindo após o identificador e entre parênteses, e o corpo entre as chaves {}. Exemplo: ``
function somar(valor1, valor2){
   return valor1 + valor2;
}
``

## FUNÇÃO DECLARATIVA 
Ao criar a função declarativa, inicia-se o código com a palavra-chave ``function``, seguida pelo identificador  e então os parâmetros desejados e depois o seu corpo com o retorno .
```
function somar(valor1, valor2){
  return valor1 + valor2;
}
```
Isso é uma função declarativa, ela pode ser chamada mesmo que esteja abaixo do código, pois ela não está definida com let nem const. Segue a mesma linha do `var`, com o hoisting.

#### desvantagem
Pode deixar seu código confuso. E não são tão flexíveis.

## FUNÇÃO EXPRESSIVA
Para criarmos uma função expressiva, utilizamos a função dentro de uma variável já com esse intuito. 
Segue uma sintaxe parecida com a declaration, mas é mais utilizada que a função declarativa.
```
let somar = function(valor1, valor2) {
  return valor1 + valor2;
};
```
Diferentemente da declarativa, ela necessita do `;` após as chaves `}`, pois é uma expressão atribuída a uma variável e não uma declaração de fato.

## FUNÇÃO ARROW
É a função mais utilizada para ações curtas, pois ela é bem resumida estruturalmente. 
```
let somar = (a, b) => a + b;
```
Só é preciso utilizar o `return` quando se usa as chaves, mas na maior parte das funções não será tão necessário o uso delas.

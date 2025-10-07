# funcoesjs
Tutorial de Funções: Como criar funções em javascript e para que servem.
## DEFININDO FUNÇÃO

Funções são blocos de código utilizados para melhorar a estrutura do código, já que trechos repetitivos <br>
Todas as funções possuem parâmetro e corpo. O(s) parâmetro(s) pode ser definido ou não ao criar a função e sempre estará entre parenteses: (), e o corpo sempre estará entre chaves: {}.

## FUNÇÃO DECLARATIVA 
Ao criarmos a função declarativa, iniciamos o código com a palavra-chave ``function``, seguida pelos parâmetros desejados e depois criamos o seu corpo com o retorno do que queremos.
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

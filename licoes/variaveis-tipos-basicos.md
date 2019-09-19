# Javascript: Variáveis & Tipos Básicos

## Variáveis

Variáveis são pontos na memória em que podemos armazenar valores mutáveis. Por exemplo:

```
var curso = 'Javascript Básico';
```

Acima defini uma variável chamada de curso, que recebeu o valor `Javascript Básico`. No decorrer da execução da minha aplicação posso atribuir valores diferentes a este ponto, variável, chamado de curso conforme a necessidade.

O valor da variável curso é a string **Javascript Básico**, caracterizada pelas aspas simples envolvendo o pequeno conjunto de caracteres. Devido o Javascript ser dinâmico, automaticamente o tipo da variável `curso` é assinalado como **string**.

Conforme eu atribuo um valor a uma variável, o tipo desta variável pode mudar, conforme o tipo do valor atribuido a ela, devido a isso a linguagem é de tipagem dinâmica. Junto da tipagem dinâmica vêm o termo fracamente tipada, uma vez que a variável recebe seu tipo com base no valor, fica dificil saber se uma variável do tipo string chegará ao fim de sua execução sendo, ainda, do tipo string uma vez que a variável não recebeu um tipo em sua definição e o tipo é atribuido com base no valor da variável.

### ES6 ou ES2015: const & let

O Javascript passou por grandes mudanças no ano de 2015, recebendo diversos incrementos. Vale ressaltar aqui que temos uma spec que define as alterações que o Javascript irá receber, no ano corrente, que se chama EcmaScript, que abreviado vira ES. 

Na versão 6 da EcmaScript o Javascript recebeu diversos incrementos e um deles foi na definição de variavéis, com a adição de duas palavras reservadas no momento da criação de uma variável: **let** & **const**.

#### let

Se você possui determinada variável que seu valor irá mutar no decorrer da sua aplicação Javascript, ao invés de você iniciar sua variável com a palavra reservada `var` é recomendado agora iniciá-la com a palavra reservada `let`, veja abaixo:

```
let curso = 'Javascript Básico';
```


#### const

Já o const, ao contrário do `let`, indica que a variável em questão não terá o valor mutável, ou seja, se você iniciar uma variável com o const você deverá seguir a execução do seu código sem alterações no valor desta variável, veja abaixo:

```
const curso = 'Javascript Básico';
```

Desta maneira, o valor de curso deverá ser o mesmo até o fim do script e mesmo que tente alterar este valor em tempo de execução você não terá sucesso.

## Tipos Básicos

O Javascript trabalha com os seguintes tipos básicos:

- Number;

```
let idade = 10;
```

- String;

```
let curso = 'Javascript Básico';
```

- Float;

```
let preco = 19.99;
```

- Booleano.

```
let ligado = true;
let desligado = false;
```





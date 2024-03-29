# Aprendendo Javascript Básico

O Javascript é uma linguagem criada por Brendan Eich, e é largamente utilizada na Web hoje em dia. O Javascript tornou-se tão popular que hoje, além de fazer seu trabalho bem feito na Web nos browsers em geral, também buscou lugar em aplicações Backend, por meio do NodeJS, e está presente na API de alguns bancos NoSQL.

O Javascript é uma linguagem interpretada, fracamente tipada, além de ser prototype-based e multi-paradgma. Com o Javascript adicionamos uma camada extra de interação com o usuário em tempo real de utilização que o HTML e o CSS não permitem diretamente. Por meio do Javascript é possivel:

- Validar campos;
- Criar efeitos de execução;
- Criar lógicas mais complexas de interface;
- É possivel por meio de APIs atuais utilizar notificações, geolocation, armazenamento de dados e muito mais.

A lista com Javascript no Frontend, ou WebBrowser, é imensa não fica só nas listadas acima mas já serve para você ter uma excelente noção do poder desta linguagem que a cada ano vêm ganhando novas funcionalidades, trazendo assim mais poder e mais possibilidades na criação de páginas web ricas.

## Linkando Javascript em nossa Página HTML

Para usar conteúdo javascript em uma página HTML você pode usar duas formas mais indicadas. São elas:

- Código na mesma página;
- Ou usando a linkagem de uma arquivo externo.

Por exemplo, vamos realizar um hello world com javascript lançando um alerta em uma página HTML simples. Pra isso crie em um local de sua escolha o arquivo `index.html` com o código abaixo:

```html
	<html>
	    <head>
	        <meta charset="UTF-8">
	        <title>Hello World Javascript</title>
	    </head>
	    <body>
	        <h1>Hello World com Javascript</h1>
	        
	        <script>
	            alert('Hello World');
	        </script>
	    </body>
	</html>
```

Para testar é só abrir o arquivo em seu browser de escolha.

Acima utilizamos o Javascript na própria página entre as tags script, que delimita onde começa e termina nosso código Javascript.

Se quisermos linkar o javascript externamente, basta realizarmos a seguinte alteração:

```html
	<html>
	    <head>
	        <meta charset="UTF-8">
	        <title>Hello World Javascript</title>
	    </head>
	    <body>
	        <h1>Hello World com Javascript</h1>
	        
	        <script src="helloWorld.js"></script>
	    </body>
	</html>
```

Agora informamos o atributo `src` da tag script que refere o caminho até o arquivo javascript em questão, em nosso caso o `helloWorld` com a extensão `.js`. 

Para o código funcionar, como está acima, crie um arquivo `helloWorld.js` na mesma pasta onde está seu `index.html` e coloque o conteúdo abaixo.

**helloWorld.js**:

```javascritp
    
    alert('Hello World');
	            
```

Como estamos lançando apenas um alert, o código se mantêm o mesmo dentro do `helloWorld.js`.

## Conteúdo do curso:

Conheça mais desta linguagem acessando os conteúdos abaixo:

- Variáveis & Tipos Básicos: [acessar](licoes/variaveis-tipos-basicos.md);
- Operadores - Aritméticos: [acessar](licoes/operadores-aritmeticos.md);
- Operadores - Comparação: acessar;
- Operadores - Lógicos: acessar;
- Estruturas de Controle - Condicionais: acessar;
- Estruturas de Controle - Laços: acessar;
- Trabalhando com Arrays e Objetos: acessar;
- Introdução a Seletores: acessar;
- Criando um pequeno app de contatos: acessar;

## Siga-nos nas redes sociais & no Youtube

Youtube: [http://youtube.com/CodeExpertsLearning](http://youtube.com/CodeExpertsLearning);

Instagram: [http://instagram.com/codeexperts](http://instagram.com/codeexperts);

Twitter: [http://twitter.com/Code_Experts](http://twitter.com/Code_Experts);

Facebook: [http://facebook.com/CodeExpertsCursos](http://facebook.com/CodeExpertsCursos);

# APRENDIZADO

# LÓGICA DE PROGRAMAÇÃO

```
Lógica de programação é nada mais nada menos, 
que uma forma de raciocínio para resolver problemas em programação.
```

```
Ex: Como você iria até a cozinha fritar um ovo para comer?
1 - Levantar da cadeira
2 - Andar até a cozinha
3 - Andar até a geladeira onde fica os ovos
4 - Abrir a geladeira
5 - Pegar os ovos
6 - Fechar a geladeira
7 - Colocar os ovos onde não caiam
8 - Pegar uma frigideira 
9 - Pegar o oleo e colocar a na frigideira
10 - Ligar o fogo
11 - Quebrar os ovos e colocar na frigideira
12 - Pegar uma colher e mexer os ovos da forma que eu preferir
13 - Após os ovos fritos desligar o fogo
14 - Pegar um Prato e colocar os ovos
```

```
Esse seria um pequeno exemplo de como funciona a lógica de algo, 
nós fazemos isso várias vezes no dia-a-dia e nem percebemos, 
quase tudo tem uma formula de se fazer e na programação não é diferente.
```

```
Ex: codigo simples da soma de 2 valores
```

 - **criando a variavel e colocando oh seu valor**
```
const val1 = 5;
```
 - **criando a segunda variavel e colocando seu valor**
```
const val2 = 3;
```

- **criando uma variavel que recebe as duas variaveis anteriores e soma as duas**
```
let result = val1 + val2;
```
- **retornando para o resultado da soma das duas variaveis, chamando a variavel que estava fazendo a operação**
```
console.log(result)
```
```
Saida = 8
```

Ou 
```
Este codigo abaixo funciona exatamente como o anterior mas com uma logica diferente e com uma refatoração que é um assunto para depois.
```
- **criando uma função que tem como argumento 2 variaveis**
```
function somar(val1,val2){
    
    return val1 + val2;
}
```
- **retornando a soma dessas duas variaveis, mas aqui é apenas o retorno interno sem mostrar no console**

- **chamando a função no console e determinando quais valores eu quero para a soma e retornando a operação-**
```
console.log(somar(5,3))
```
```
Percebam que oh codigo executa exatamente aquilo que eu mandei ele fazer, lógica de programação é isso,
você determina a logica de como vai resolver um problema e o computador executa, 
mas caso essa lógica não faça sentido o computador mesmo assim vai fazer oque você mandou,
e mesmo que não siga a lógica vai executar, 
a diferença é que ele não vai te entregar um resultado que você espera ou vai dar um erro.

Isso é um pouco sobre logica de programação e como eu entendo, 
vou deixar um sites abaixo onde eu treino a minha lógica de programação nas linguagens com que eu trabalho, 
e lembrando a lógica é promordial para qualquer linguagem que você escolha.
```

- **Sites para treinar lógica**
```
https://www.beecrowd.com.br
https://leetcode.com/
```

# SOLID

```
S = SINGLE RESPONSABILITY PRINCIPLE
- Cada classe metodo e afins tem a sua responsabilidade, um service serve somente para montagem de metodos, 
como um controller em Java serve somente para fazer a ligação REST. 
```

```
O = OPEN CLOSED PRINCIPLE
- Esse princípio nos diz que, ao criar um objeto ou entidade, devemos prepará-lo para que possa ser implementado por outro futuramente.
 Assim, não será necessário modificar o objeto pai.
```

```
L = LISKOV SUBISTITUTION PRINCIPLE
- Sendo mais direto, esse princípio nos diz que, se uma função necessita de uma classe que está sendo implementada por outras,
 podemos utilizar tanto a classe base quanto as classes que são derivadas desta primeira. Isso porque todas seguem os mesmos padrões,
 alterando apenas as implementações da original.
```

```
I = INTERFACE SEGREGATION PRINCIPLE
- Esse princípio mostra que devemos criar interfaces mais específicas para nossos objetos,
 ao invés de uma classe mais genérica para todos do mesmo tipo.
```

```
D  = DEPENDENCY INVERSION PRINCIPLE 

Sobre esse princípio, Uncle Bob nos confere duas definições:

“Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração”;
“Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações”.
Com a Inversão de Dependência, conseguimos desacoplar nossas classes de bibliotecas específicas e 
fazer com que outras ferramentas possam ser utilizadas no lugar desta primeira. Assim, 
as classes utilizarão abstrações de interfaces ao invés de outras classes ou de instâncias objetos. 
```
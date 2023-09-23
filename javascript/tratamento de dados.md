# Anotações do javascript

## Convertendo variaveis

Usando `Number.parseInt(var)` para numeros inteiros e `Number.parseFloat(var)` para numeros flutuantes (com casas decimais).

~~~javascript
    var n1 = window.prompt('escolha um numero ')
    var n2 =  window.prompt('escolha outro numero')
    var soma = Number.parseFloat(n1) + Number.parseFloat(n2)
    window.alert('a soma dos numeros é ' + s)
~~~

Usando apenas `Number(var)`, o proprio javascript interpreta se é inteiro ou flutuante.

~~~javascript
    var n1 = window.prompt('escolha um numero ')
    var n2 =  window.prompt('escolha outro numero')
    var soma = Number(n1) + Number(n2)
    window.alert('a soma dos numeros é ' + s)
~~~

Para converter um numero em string é bem parecido

~~~javascript
    var n1 = 3
    window.alert('o numero é ' + String(n1))
~~~

## Formatando strings

Concatenações são usadas assim.

~~~javascript
    var nome = 'alexsandro'
    var idade = 26

    window.alert('meu nome é ' + nome + 'e tenho ' + idade + ' anos!')
~~~

Usamos no novo ECMAscript o template string que é bem mais legivel e facil.

~~~javascript
    var nome = 'alexsandro'
    var idade = 26

    window.alert('meu nome é ${nome} e tenho ${idade} anos!')
~~~

Usando o `var.lenght`, `var.toUppercase()` e `var.toLowerCase()`.

~~~javascript
    var nome = window.prompt('qual seu nome?')
    document.write(`seu nome tem ${nome.length} letras <br>`)
    document.write(`ele escrito em maiusculo fica assim ${nome.toUpperCase()}<br>`)
    document.write(`ele escrito em minusculo fica assim ${nome.toLowerCase()}`)
~~~

Usando o `toFixed()` para formatar os numeros em quantidades de casas decimais

~~~javascript
    var n1 = 1545.5
    document.write(n1.toFixed(2))
~~~

Usando o `toFixed().replace()` você pode alterar o ponto por virgula

~~~javascript
    var n1 = 1545.5
    document.write(n1.toFixed(2).replace('.',','))
~~~

Um metodo avançado de fazer virar uma moeda de um país

~~~javascript
    var n1 = 1545.5
    document.write(n1.toLocaleString('pt-BR' , {style: 'currency', currency: 'BRL'}))
~~~
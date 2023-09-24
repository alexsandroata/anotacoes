# Anotações

##Operadores

* Aritimeticos
* Atribuição
* Relacionais
* Logicos
* Ternario

## Operações aritiméticas

~~~javascript
5 + 2 = 7 //Soma
5 - 2 = 3 //Subtração
5 * 2 = 10 //Multiplicação
5 / 2 = 2.5 // Divisão
5 % 2 = 1 // Resto da divisão inteira
5 ** 2 = 25 //Ao quadrado (Potencia)
~~~

cuidado com precedencias

~~~javascript
5 + 3 / 2 = 6.5
(5 + 3) / 2 = 4
~~~

### Precedencia das aritimeticas

* `()`
* `**`
* `*, / e %`
* `+ e -`

## Operações de atribuição

o simbolo igual sozinho significa "receber"

~~~javascript
    var nome = "Alexsandro" //variavel nome "recebe" Alexsandro
~~~

### Auto-atribuição simples, simplificado e incremento

~~~javascript
    var n = 3
    var n = n + 4 //simples

    var m = 3
    var m += 4 //simplificado

    var o = 3
    o++ //incremento
~~~

## Operações relacionais

~~~javascript
    5 > 2 //TRUE maior
    7 < 4 //FALSE menor
    8 >= 8 //TRUE maior ou igual
    9 <= 7 //FALSE menor ou igual
    5 == 5 //TRUE igual
    4 != 4 //FALSE diferente
~~~

 Relacionais com identidade

~~~javascript
    5 == 5 //TRUE
    5 == '5' //TRUE
    5 === 5 //FALSE (identidade é igual)
~~~

## Operações logicos

~~~javascript
    ! //negação
    && //conjunção
    || //dijunção
~~~

## Operações ternarios

~~~javascript
    teste ? true : false
~~~

exemplo

~~~javascript
    x = 8
    res = x + 1
    res > 8 ? 'Aprovado' : 'reprovado' //variavel res recebe aprovado
~~~


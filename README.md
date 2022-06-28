# Comandos_'Básicos_JavaScript'
Comandos básicos de JavaScript para iniciantes


* * * Tipos de dados * * * 
 _____________
| String      |
| boolean     |
| null        |
| undefined   |
| function    |
|             |
| Number      |
|  infinity   |
|  NaN        |
|             |
| object      |
|   Array     |
|_____________|

typeof // mostra a tipagem das variável ou dados
 
exemplos:

var n = 100
 
typeof n
'number'

typeof 6 
'number'

typeof 'Google'
'string'

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Declarações de variáveis no js

 var $nome = 'Daniel'
 var $segundo_nome = "Victor"
 var _nome = 'Daniel'
 var nome = 'Daniel';  
 var nome = "Daniel"
 nome = 'Daniel'                  
 var salario = 10
 
  
       Or                           /* OBS: Podemos usar acentos ou símbolos como por exemplo: var vírgula = ',' 
                                            NÃO podemos deixar espaços em branco como por exemplo: var nome sobrenome
                                            NÃO podemos começar com número como por exemplo: 1nome 
                                            NÃO podemos utilizar palavras reservadas como por exemplo: var let = 10
                                            Maiúsculas e Minúsculas fazem diferença */

 let nome = 'Daniel'; 
 let nome = "Daniel"
 let $nome = 'Daniel'
 $nome = 'Daniel'
 let _nome = 'Daniel'
 nome = 'Daniel'
 let $segundo_nome = "Victor"
 nome = 'Daniel'
 var salario = 10.99 

 nome = window.alert() // exemplo de atribuição com função.

// Podemos atribuir valores inteiros e reais para as nossas variávies.
// Podemos atribuir função.
// Podemos atribuir objto.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Eventos do js

window.alert() // mostra uma janela com  as imformações  e também com o botão: ok.
window.prompt() // mostra uma janela para o usuário digitar e também com o botões ok.
window.confirm() // mostra uma janela com o botão: ok.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Comentários do js
 
/* comentário de várias linhas
  text
  text
  text
  text
*/ 

// comentário de uma única linha

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Exemplo de converção de dados:

n1 = Number(window.prompt('Informe um número'))
n2 = 10.90
soma = n1 + n2;
window.alert('O valor da soma é: ' + soma.toFixed(2))    //Esse método faz o nosso valor ficar com duas casas depois do ponto
                                                        // OBS podemos colocar a quantidade que desejarmos dentro dos parênteses. 

Number.parseInt(n1)
Number.parseFloat(n1)
String(n2)
n2.toString()

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



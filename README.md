## Aula de Sintaxe 2


### Padrão de nomenclatura:

**Todo arquivo** .java deve começar com letra maiúscula. Palavras compostas, a inicial de cada uma delas deverá ser maiúscula.

Ex: [Calculadora.java](http://Calculadora.java) / CalculadoraCientifica.java

**Nome da classe no arquivo**: A classe deverá possuir o mesmo nome do arquivo.java

Ex: public class MinhaClasse / public class Aula1

**Nome de variável**: toda variável deverá ser escrita em letra minúscula. Porém, se a palavra for composta, a primeira letra de cada nova palavra deverá ser maiúscula.

Ex: ano / anoFabricacao

A prática para nomear variáveis dessa forma se chama camelCase

Existe uma regra adicional para variáveis, que é quando queremos identificar que esta variável nunca sofrerá alteração em seu valor.
Ex: variável br sempre representará Brasil, e nunca mudará seu valor. Logo, determinamos sua escrita como: 

**OBS**: a variável que não mudará seu valor, é comumente escrita em letras maiúsculas, precedida pela sintaxe **final**

String BR = “Brasil”

double PI = 3.14

int ESTADOS_BRASILEIROS = 27

int ANO_2000 = 2000

Variáveis devem conter apenas letras, _ (underline), $ ou números de 0 a 9

Deve obrigatoriamente se iniciar com uma letra (preferencialmente), _ ou $. **JAMAIS** iniciar variável com números.

Deve iniciar com uma letra minúscula (boa prática)

Não pode conter espaços

Não podemos usar palavras chave da linguagem (erros acontecem)

O nome da variável deverá ser único dentro de um escopo

# **Declarando variáveis e métodos**

Existe uma estrutura em Java quando formos declarar uma variável:

Tipo NomeBemDefinido = Atribuição (opcional em alguns casos)

Ex:

int idade = 23;

double altura = 1.62;

Dog spike;

Boolean é uma variável para atributos lógicos.

## **Métodos**

TipoRetorno NomeObjetivoNoInfinitivo Parâmetro (s)

(métodos em Java levam nome no **infinitivo!**

Ex:

int somar (int numeroUm , int numero2)

String formatarCep (long cep)

### **Aula 4**

Identação: identar é um termo utilizado para escrever o código do programa de forma hierárquica, facilitando a visualização e o entendimento do programa.

Apertar “tab” para tabulação. (só será realizada a ação mediante entrar na ação anterior)

# Entrada e saída de dados (I/O) em Java

> Basicamente é a forma como seu programa recebe **informações (entrada)** e como ele mostra **informações (saída)**. 

---

## 1. Saída: 
- O objeto **System.out** representa a saída padrão, permitindo exibir dados no console quando executamos uma aplicação em Java. O **System.out** possui diversos métodos para gerar saídas, sendo os mais utilizados os métodos **println**, **printf** e **print**.

<br>

## ✨Método **println()**

O método **System.out.println()** gera uma string de texto, cria uma nova linha abaixo da atual e então posiciona o cursor nesta linha. 

**Exemplos:**

```
System.out.println("Estou sem dinheiro...");
System.out.println("Preciso de um telefone novo!");
```

<br>

## ✨ Método **printf()**

O método **System.out.printf()** mostra os dados na saída formatados. Um especificador de formato se inicia com o símbolo *%*, seguindo por um caractere que representa o tipo de dado.  

**Exemplos:**

```
Double numDecimal = 23.8954;
int minhaIdade = 17;
String meuNome = "Yasmiiiinn";
char gremio = 'G';

System.out.printf("Número = %.2f%n" , numDecimal);
System.out.printf("Minha idade = %.2d&n" , minhaIdade);
System.out.printf("Meu nome = %.2s%n" , meuNome);
System.out.printf("Primeira letra = %C" , gremio);
```
<br>

## ✨ Método **print()**

O método **System.out.print()** gera uma string de texto, porém diferentemente do metodo **println()**, não cria uma nova inha abaixo da atual, deixando o cursor na mesma linha onde a string foi impressa.

**Exemplo:**
```
System.out.print("Preciso de um telefone novo, o meu está caindo a parte de trás...");
System.out.print("E um fone novo seria legal hehe!");
```

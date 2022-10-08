1.A JVM não é nada mais do que uma máquina virtual que deixa o hardware e a plataforma visível a aplicação, em que as seguintes funções:

-Interpreta o Bytecode Java para ser executado no SO (o arquivo tem contém o o .class 
gerado pela compilação do .java), faz a Checagem de erros em tempo real e gerenciamento automático de memória.



2-O JDK é um ambiente para desenvolvimento de software que são usados ​​para desenvolver aplicativos de 
Java em plataformas Java. Já o JRE é uma parte do JDK que fornece o requisito mínimo para executar os programas Java.


3- Primeria parte compilei  o arquivo ulizando javac, gerou um aquivo Programa.class.


4- excultei o arquivo com segunte codigo java Programa imprimil= "Terminei a primeira aula com um programa Java!"


5- excluir arquivo compilado chamado Programa.class, gerando o erro abaixo.
Error: Could not find or load main class Programa
Caused by: java.lang.ClassNotFoundException: Programa


6- ao compilar com start no lugar no main, foi aceito e compilado, no entando dar erro na execulção.
Error: Main method not found in class Programa, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application

7 - Ao tenta excultar tudo em minusculo foi imprimido o seguinte erro.
fotebol.java:1: error: class time is public, should be declared in a file named time.java
public class time {
       ^
fotebol.java:3: error: cannot find symbol
    public static void main(string[] args) {
                            ^
  symbol:   class string
  location: class time
fotebol.java:4: error: package system does not exist
        system.out.println("iago alves");
              ^
fotebol.java:5: error: package system does not exist
        system.out.println("Corinthians");
8- ao tenta compilar com nome do arquivo diferente da classe, foi imprimido o segunte erro.
Futebol.java:1: error: class Time is public, should be declared in a file named Time.java
public class Time {
       ^
1 error
 





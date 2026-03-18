# exercicio-1-de-java
aula 1

Desafio 1 = Peça para o usuário digitar um número e exiba esse número multiplicado por 2.

import java.util.Scanner;

public  class Dobro{

    public static void main(String[] args) {

        Scanner ler = new Scanner(System.in);
            int num;

            System.out.print("Insira um número: ");
            num = ler.nextInt();

            System.out.print("O dobro de " + num + " é " + 2*num);
    }
}

Desafio 2 = Leia dia, mês e ano de nascimento de uma pessoa e imprima na tela para conferência.

import java.time.LocalDate;
import java.util.Scanner;

public class nasc {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        System.out.print("Digite o dia de seu nascimento: ");
        int dia = ler.nextInt();

        System.out.print("Digite o mês de seu nascimento: ");
        int mes = ler.nextInt();

        System.out.print("Digite o ano de seu nascimento: ");
        int ano = ler.nextInt();

        LocalDate data = LocalDate.of(ano, mes, dia);
        System.out.println("Seu nascimento é na data: " + data);

        ler.close();
    }
}

Desafio 3 = Crie um programa que leia dois números e mostre a soma deles.

import java.util.Scanner;

public class Soma {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        System.out.print("Digite o primeiro número: ");
        int num1 = ler.nextInt();
        System.out.print("Digite o segundo número: ");
        int num2 = ler.nextInt();

        System.out.print("A soma dos números é: " + (num1 + num2));
    }
}

Desafio 4 = Faça um programa que leia um número inteiro e mostre na tela o seu antecessor e sucessor.

import java.util.Scanner;

public class numInt {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        System.out.print("Digite um número: ");
        int num = ler.nextInt();

        System.out.println("O antecessor deste número é: " + (num- 1));
        System.out.println("O Sucessor deste número é: " + (num+1));

    }
}

!! desafio bonus 1 = Peça ao usuário um número inteiro e mostre na tela o triplo desse número e a metade desse número com decimal.

import java.util.Scanner;

public class triplo {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        System.out.print("Digite um número: ");
        int num = ler.nextInt();

        System.out.println("O triplo deste número é: " + (num * 3));
        System.out.println("A metade do triplo é: " + (num/2.0));
    }
}

!! desafio bonus 2 = Peça ao usuário um número inteiro e some o antecessor e o sucessor deste número.

import java.util.Scanner;

public class soma2 {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        System.out.print("Digite um número: ");
        int num = ler.nextInt();

        System.out.println("O antecessor é: " + (num-1));
        System.out.println("O sucessor é: " + (num+1));
        System.out.println("A soma do Antecessor e o sucessor deste número é: " + (num-1 + num+1));
    }
}



Estruturas de repetição e de condionais em Java

public class Notas {
    //for (<variável de controle>, <análise da variável de controle>, <incremento da variável de controle>) {
        // Código a ser executado
    //}
    //exemplo com For:

    //public class Exemplo {
    //
    //    public static void main(String[] args) {
    //        for (int i = 0; i <= 10; i++) {
    //            System.out.println(“A variável i agora vale “ + i);
    //        }
    //    }
    //
    //}




    //while (<condição>) {
    //    // Trecho de código a ser repetido
    //}
    //exemplo com while:

    //public class Exemplo {
    //  public static void main(String[] args) {
    //      Scanner in = new Scanner(System.in);
    //      int numero = -1;
    //      while (numero != 10) {
// enquanto a variável não for 10, o trecho de código será repetido
    //          System.out.println(“Digite um número: “);
    //          numero = in.nextInt();
    //          if (numero == 10) {
    //          System.out.println(“Você acertou!“);
    //          } else {
    //          System.out.println(“Você errou :(“);
    //          }
    //       }
    //  }
    //}





    //Switch/Case

    //public class Exemplo {
    //
    //    public static void main(String[] args) {
    //        int mes = 2;
    //        switch (mes) {
    //            case 1:
    //                System.out.println(“O mês é janeiro”);
    //                break;
    //            case 2:
    //                System.out.println(“O mês é fevereiro”);
    //                break;
    //            case 3:
    //                System.out.println(“O mês é março”);
    //                break;
    //            case 4:
    //                System.out.println(“O mês é abril”);
    //                break;
    //            case 5:
    //                System.out.println(“O mês é maio”);
    //                break;
    //            case 6:
    //                System.out.println(“O mês é junho”);
    //                break;
    //            case 7:
    //                System.out.println(“O mês é julho”);
    //                break;
    //            case 8:
    //                System.out.println(“O mês é agosto”);
    //                break;
    //            case 9:
    //                System.out.println(“O mês é setembro”);
    //                break;
    //            case 10:
    //                System.out.println(“O mês é outubro”);
    //                break;
    //            case 11:
    //                System.out.println(“O mês é novembro”);
    //                break;
    //            case 12:
    //                System.out.println(“O mês é dezembro”);
    //                break;
    //            default:
    //                System.out.println(“Mês inválido”);
    //                break;
    //        }
    //    }
    //
    //}


//Estruturas Condicionais:
    //exemplo onde o if é utilizado em conjunto com o else.
    //

    //public class Exemplo {
    //
    //    public static void main(String[] args) {
    //        int resposta = 10;
    //        if (resposta == 10) {
    //            // Se a variável for igual a 10, a frase abaixo será escrita
    //            System.out.println(“Você acertou!”);
    //        } else {
    //            // Caso contrário, a frase abaixo será escrita
    //            System.out.println(“Você errou!”);
    //        }
    //    }
    //
    //}


    //Também podemos utilizar somente o if, não definindo um fluxo alternativo.
    //

    //public class Exemplo {
    //
    //    public static void main(String[] args) {
    //        int resposta = 10;
    //        if (resposta == 10) {
    //            // Se a variável for igual a 10, a frase abaixo será escrita
    //            System.out.println(“Você acertou!”);
    //        }
    //        // Se a variável não for igual a 10, nenhuma frase será exibida
    //    }
    //
    //}


    //Ainda é possível encadear múltiplas estruturas if/else caso necessário.
    //

    //public class Exemplo {
    //
    //    public static void main(String[] args) {
    //        int resposta = 10;
    //        if (resposta == 10) {
    //            System.out.println(“A resposta é exatamente 10!”);
    //        } else if (resposta > 10) {
    //            System.out.println(“A resposta é maior que 10!”);
    //        } else {
    //            System.out.println(“A resposta é menor que 10!”);
    //        }
    //    }
    //
    //}
}

# Conta-Banc-ria
Neste repositório me desafiei em resolver um problema básico de programação bancária, aonde poderei receber alguns dados de qualquer usuário para poder mostrar na tela o seu saldo.



Crie o projeto ContaBanco que receberá dados via terminal contendo as caracteristicas de conta em banco conforme atributos abaixo:
         * Dentro do projeto, crie a classe Banco.java para realizar toda a codificação do nosso programa.
         * Numero - Inteiro - 1021;
         Agencia - Texto - 067-8 ;
         * Nome Cliente - Texto - Sebastião Pedro;
         Saldo - Decimal - 237,48.
         * NOTA: Revise sobre terminal, main args e a classe Scanner
         * 2 -- Permita que dados sejam inseridos via terminal sendo que o usuário receberá a mensagem de qual informação será solicitado.  exemplo :
         * Programa : "Por favoe, digite o numero da agencia!"
         * Usuário : 101 (depois enter para o próximo passo)
         NOTA: Revise sobre concatenação e classe String com método concat.
         * 3 -- Depois de todas as informações terem sido inseridas, o sistema deverá exibir a seguinte mensagem :
         * "Olá [NomeCliente], obrigado por criar uma conta em nosso banco, sua agencia é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque."
         * Os campos [] devem ser alterados pelas informações que forem inseridas pelos usuários.


         import java.util.Scanner;
public class Banco {
    public static void main(String[] args) throws Exception {
        /**
         * Crie o projeto ContaBanco que receberá dados via terminal contendo as caracteristicas de conta em banco conforme atributos abaixo:
         * Dentro do projeto, crie a classe Banco.java para realizar toda a codificação do nosso programa.
         * Numero - Inteiro - 1021; Agencia - Texto - 067-8 ;* Nome Cliente - Texto - Sebastião Pedro; Saldo - Decimal - 237,48.
         * NOTA: Revise sobre terminal, main args e a classe Scanner
         * 2 -- Permita que dados sejam inseridos via terminal sendo que o usuário receberá a mensagem de qual informação será solicitado.  exemplo :
         * Programa : "Por favoe, digite o numero da agencia!"
         * Usuário : 101 (depois enter para o próximo passo)
         NOTA: Revise sobre concatenação e classe String com método concat.
         * 3 -- Depois de todas as informações terem sido inseridas, o sistema deverá exibir a seguinte mensagem :
         * "Olá [NomeCliente], obrigado por criar uma conta em nosso banco, sua agencia é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque."
         * Os campos [] devem ser alterados pelas informações que forem inseridas pelos usuários.
         */

        /* int numeroDaConta = 1021;
         String Agencia = "067-8";
         String nomeDoCliente = "Sebastião Pedro";
         double saldoDaConta = 237.48;
        */
        
        Scanner banco = new Scanner(System.in);
        
        System.out.println ("Qual é o seu nome? ");
        
        String nomeDoCliente = banco.nextLine();
        
        System.out.println ("Digite abaixo o número da sua agência :");
        
        String Agencia = banco.nextLine();
        
        System.out.println ("Digite abaixo o número da sua conta : ");
        
        int numeroDaConta = banco.nextInt();
        
        double saldoDaConta = 237.48;
        
        System.out.println ("Olá sr. " + nomeDoCliente + ", obrigado por ter criado conta em nosso banco, sua agencia é " + Agencia + " numero da conta é " + numeroDaConta + " e o seu saldo " + saldoDaConta + "BRL já está disponível para saque.");
        
    
      
        
        
    }
}


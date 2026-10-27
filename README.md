# Anotações de Java: repetição e condicionais

Caderno de consulta sobre `for`, `while`, `switch/case` e `if/else`. O repositório contém apenas este README: os exemplos são material didático, não uma aplicação Java pronta.

## Estrutura de um programa

Para experimentar, crie um arquivo `Exemplo.java` fora deste README e coloque um trecho dentro de `main`:

```java
public class Exemplo {
    public static void main(String[] args) {
        // Insira aqui um dos trechos abaixo.
    }
}
```

Com um JDK instalado, compile com `javac -encoding UTF-8 Exemplo.java` e execute com `java Exemplo`. Use aspas retas (`"`) nas strings. Teste cada exemplo separadamente.

## for: repetição com controle

A inicialização ocorre uma vez; a condição é verificada antes de cada volta; a atualização ocorre após o corpo.

```java
for (int i = 0; i <= 10; i++) {
    System.out.println("A variável i agora vale " + i);
}
```

Este exemplo imprime de 0 a 10, inclusive: 11 repetições.

## while: repetição enquanto a condição for verdadeira

O exemplo original pede números até o usuário informar 10. Adicione `import java.util.Scanner;` antes da classe ao usar este trecho:

```java
Scanner in = new Scanner(System.in);
int numero = -1;
while (numero != 10) {
    System.out.println("Digite um número:");
    numero = in.nextInt();
    if (numero == 10) {
        System.out.println("Você acertou!");
    } else {
        System.out.println("Você errou :(");
    }
}
```

A condição é testada antes do corpo; por isso, um `while` pode executar zero vezes. O exemplo pressupõe entrada inteira, sem tratamento para texto inválido.

## switch/case: seleção por valor

```java
int mes = 2;
switch (mes) {
    case 1:
        System.out.println("O mês é janeiro");
        break;
    case 2:
        System.out.println("O mês é fevereiro");
        break;
    case 3:
        System.out.println("O mês é março");
        break;
    default:
        System.out.println("Mês fora deste exemplo");
        break;
}
```

O exemplo foi reduzido aos três primeiros meses para destacar a estrutura. Para mapear o ano completo, acrescente os casos de 4 a 12. `break` encerra o `switch`; sem ele, o fluxo pode continuar nos casos seguintes. `default` atende valores não tratados.

## if, else e else if: decisões

```java
int resposta = 10;
if (resposta == 10) {
    System.out.println("Você acertou!");
} else {
    System.out.println("Você errou!");
}
```

O `else` é opcional. Para testar mais de uma condição:

```java
int resposta = 10;
if (resposta == 10) {
    System.out.println("A resposta é exatamente 10!");
} else if (resposta > 10) {
    System.out.println("A resposta é maior que 10!");
} else {
    System.out.println("A resposta é menor que 10!");
}
```

## Cuidados para estudar

- `=` atribui um valor; `==` compara os inteiros usados aqui.
- Não coloque `;` entre a condição de um `if` ou `while` e seu bloco.
- Em repetições, garanta que a condição possa mudar para evitar um laço infinito.
- Altere limites e valores iniciais e preveja a saída antes de executar.

Não há fontes `.java`, testes ou configuração Maven/Gradle versionados. Esta revisão organiza e corrige a apresentação dos exemplos dentro da documentação.

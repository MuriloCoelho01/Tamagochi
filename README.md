# Tamagochi

Este é um jogo de console em Kotlin que simula a interação com um pet virtual. Você será responsável por cuidar do seu Tamagochi, mantendo-o alimentado, feliz e descansado enquanto ele envelhece. O objetivo é mantê-lo vivo e saudável até que ele atinja 50 anos de idade.

---

## Funcionalidades

- **Nome do Pet**: Escolha o nome do seu Tamagochi no início do jogo.
- **Interações com o Pet**:
  - **Alimentar**: Diminui a fome do Tamagochi.
  - **Brincar**: Aumenta a felicidade, mas também aumenta a fome e o cansaço.
  - **Dormir**: Reduz o cansaço.
- **Status do Pet**: Exibe as informações atuais do Tamagochi, como fome, felicidade, cansaço, idade e vida.
- **Passar Tempo**: Após cada interação, o tempo passa e os atributos do Tamagochi mudam automaticamente.
- **Condição de Vitória**: Se o Tamagochi alcançar 50 anos, você vence o jogo!
- **Condição de Derrota**: O Tamagochi morre se:
  - A fome atingir ou ultrapassar 100.
  - O cansaço atingir ou ultrapassar 100.
  - A felicidade cair para 0 ou menos.

---

## Como Jogar

1. Clone ou baixe o repositório com o código.
2. Abra o projeto em seu ambiente de desenvolvimento Kotlin (como IntelliJ IDEA).
3. Execute o arquivo principal que contém a função `main()`.
4. Insira o nome do seu Tamagochi.
5. Interaja com o menu:
   - **1 - Alimentar**: Reduz a fome.
   - **2 - Brincar**: Aumenta a felicidade e fome, mas também cansa.
   - **3 - Dormir**: Reduz o cansaço.
   - **4 - Verificar Status**: Mostra o estado atual do Tamagochi.
   - **5 - Sair**: Finaliza o jogo.

---

## Exemplo de Execução

```plaintext
Olá, seja bem-vindo ao Tamagochi!
Insira o nome do seu pet:
Bob

1 - Alimentar o Bob
2 - Brincar com o Bob
3 - Dormir
4 - Verificar Status
5 - Sair

Escolha uma ação: 1
Estou alimentado! nham, nham!

1 - Alimentar o Bob
2 - Brincar com o Bob
3 - Dormir
4 - Verificar Status
5 - Sair


# Desafio: Jogo da Forca em Java

Neste desafio, você deverá implementar um jogo da forca simples em Java. O objetivo é criar um programa interativo em que o jogador tente adivinhar uma palavra secreta, letra por letra, dentro de um número limitado de tentativas.

## Requisitos do Desafio

1. **Palavra Secreta**  
   - O programa deve armazenar uma palavra secreta escolhida aleatoriamente a partir de uma lista pré-definida.
   - Use uma lista com pelo menos 5 palavras diferentes.

2. **Interação com o Jogador**  
   - O programa deve exibir o progresso da palavra (letras adivinhadas e traços para letras não adivinhadas).  
     Exemplo: Para a palavra secreta "JAVA", se o jogador já adivinhou as letras 'J' e 'A', o progresso exibido deve ser: `J A _ A`.
   - Permitir que o jogador insira uma letra por tentativa.
   - Notificar o jogador se a letra adivinhada está ou não na palavra.

3. **Contagem de Tentativas**  
   - O jogador deve ter um número limitado de tentativas para adivinhar a palavra (por exemplo, 6 tentativas).  
   - Exibir a quantidade de tentativas restantes após cada jogada.

4. **Condições de Vitória e Derrota**  
   - O jogador vence se adivinhar todas as letras da palavra antes de esgotar as tentativas.  
   - O jogador perde se as tentativas chegarem a zero antes de adivinhar toda a palavra.

5. **Mensagens Finais**  
   - Ao final do jogo, exibir uma mensagem indicando se o jogador venceu ou perdeu.  
   - Caso o jogador perca, exibir a palavra secreta.

Boa sorte e divirta-se programando!

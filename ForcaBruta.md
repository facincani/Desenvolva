# Problema: Quebra de Senha Força Bruta
## Descrição
Escreva um programa que implemente uma quebra de senha utilizando o método de força bruta. O programa deve:
1. Solicitar que o usuário digite uma senha de **4 dígitos positivos**.
2. Testar todas as combinações possíveis de números entre `0000` e `9999` até descobrir qual é a senha.
3. Ao encontrar a senha:
   - Exibir o número de tentativas realizadas.
   - Mostrar o tempo total gasto para quebrar a senha.
## Notas
- Para capturar o tempo atual em milissegundos, utilize o seguinte trecho de código:  
  ```java
  System.currentTimeMillis();

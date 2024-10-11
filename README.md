# Método da Bissecção 

O método da bissecção é utilizado para encontrar raízes de funções contínuas. Ele começa com um intervalo onde a função muda de sinal (ou seja, tem uma raiz). A cada iteração, o intervalo é dividido ao meio, e o subintervalo que contém a raiz é escolhido para a próxima iteração, repetindo o processo até que a precisão desejada seja atingida.

# Como rodar

![Print do terminal mostrando como executa o programa](screemshot.png)

Para compilar use: `./mb -o mb main.c -lm `
  - -lm pois estamos usando biblioteca matematica

  Já para roda use `mb 0.0 1.0 0.0001` 
  - Primeiro primeiro parametro é o executável
  - O segundo o terceiro são os extremos do intervalo de iteração
  - O ultimo é o erro permitido

  # A função
  A função usada no código é x - cos(x) 

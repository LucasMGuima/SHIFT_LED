# SHIFT LED

Este projeto consiste em mudar o LED que está atualmente aceso utilizando de dois botões, para mover para esquerda ou para direita.

## Funcionamento

Video de referencia: [YouTube](https://youtube.com/shorts/YSDwbrjQ-3A?feature=share)

O circuito possui 8 leds, que se alternam entre oque está aceso no momento. No inicio apenas um LED fica aceso.

Para alterar o LED que está aceso, se utiliza dos dois botões presentes, o botão ligado a porta B1 move o LED aceso para a esquerda, o botão ligado a porta B0 move o LED aceso para a direita.

Na situação onde o LED mais a direita está aceso, e queremos mover para a direta novamente, o LED mais a esquerda será aceso, simulando um efeito de carrocel infinito. O mesmo ocorre na situação onde o LED mais a esquerda está aceso, e quermos mover para a esquerda.

## Componentes

- 8x LEDs verdes;
- 8x RES 68 Ω;
- 74HC595;
- 2x Chave Táctil (2 Pinos);
- STM32F103C8T6.

## Montagem

- Esquema do Projeto

![Esquema](./Imagens/Circuito.jpg)

- Circuito fisico

![Fisico](./Imagens/Fisico02.jpeg)
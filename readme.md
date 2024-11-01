# Montagem física
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, segue a imagem da montagem física do arduíno em que é feito o controle do semáforo. Dentro da pasta "assets" existe um arquivo de nome "video-semaforo.mp4" que mostra a execução do semáforo em vídeo.

<img src="assets/foto-semaforo.jpg">

&nbsp;&nbsp;&nbsp;&nbsp; A montagem foi feita de maneira em que o polo positivo de cada LED, passando por um resistor, foi conectado a uma porta digital. Já os polos negativos, foram conectados lado a lado na protoboard. Um fio sai de todos esses polos negativos e vai para uma haste do interruptor. Da outra haste desse interruptor sai um fio que conecta-se ao GND. Por meio desse interruptor, pode-se interromper a corrente, dando ao usuário a possibilidade de abrir ou fechar o circuito.

## Tabela de componentes
| Componente     | Quantidade | Especificações                          |
|----------------|------------|-----------------------------------------|
| Arduino Uno    | 1          | 5V e 14 pinos digitais |
| LED            | 1          | Vermelho                   |
| LED            | 1          | Amarelo                   |
| LED            | 1          | Verde                   |
| Resistores     | 3          | 330ohm  |
| Protoboard     | 1          | 400 pontos        |
| Jumpers   | 10        | Fios conectores |

# Avaliação em Pares

### Avaliador: Nome do Avaliador

| Critério                                                                                                 | Contempla (Pontos) | Contempla Parcialmente (Pontos) | Não Contempla (Pontos) | Observações do Avaliador |
|---------------------------------------------------------------------------------------------------------|--------------------|----------------------------------|--------------------------|---------------------------|
| Montagem física com cores corretas, boa disposição dos fios e uso adequado de resistores                | Até 3              | Até 1,5                            | 0                        |                           |
| Temporização adequada conforme tempos medidos com auxílio de algum instrumento externo                  | Até 3              | Até 1,5                          | 0                        |                           |
| Código implementa corretamente as fases do semáforo e estrutura do código (variáveis representativas e comentários) | Até 3              | Até 1,5                          | 0                        |                           |
| Extra: Implmeentou um componente de liga/desliga no semáforo e/ou usou ponteiros no código | Até 1              |  Até 0,5                         | 0                        |                           |
|  |                                                             |  | |**Pontuação Total**|
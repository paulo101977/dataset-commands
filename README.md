# Dataset Commands em português

<br>
O objetivo deste repositório é criar um Dataset de comandos na língua portuguesa.
<br>
O projeto visa criar o dataset e treinar um modelo a fim de dar suporte a scripts de Tensorflow Lite.
<br>
Por fim, espero converter o modelo e permitir seu uso em sistemas embarcados, como FreeRTOS, Arduino, Micropyton,
<br>
CircuitPython e outros...

<br>
<br>

## Uma breve lista de comandos...

<br>

Atualmente os comandos do [Tensorflow Speech Commands](https://developer.ibm.com/exchanges/data/all/speech-commands/) serão os
utilizados por este projeto:

<br>

```
commands = [
    "Sim", "Não", "Cima", "Baixo", "Esquerda",
    "Direita", "Ligado", "Desligado", "Parar", "Vai",
    "Zero", "Um", "Dois", "Três", "Quatro", "Cinco", "Seis",
    "Sete", "Oito", "Nove", "Cama", "Pássaro", "Gato", "Cachorro", 
    "Feliz", "Casa", "Marvin", "Sheila", "Árvore", "Uau", "Trás", 
    "Avançar", "Seguir", "Aprender", "Visual"
]
```

<br>

## Scripts...

<br>
Dentro da pasta notebook, deixei um script para converter os áudios de falantes em comandos.
<br>
Para cada comando da lista de comandos, eu gero um arquivo de áudio com o label correspondente e seu falante, obedecendo o padrão
<br>
`{label}_{falante}.wav`
<br>
<br>

Exemplo:
<br>
Falante Araujo comando Falar gera o arquivo `Falar_Araujo.wav`

<br>

## Pasta Speakers...

<br>
A Pasta speakers contém todos os falantes necessários para treinar o modelo.
<br>
Os falantes são necessários para obter uma grande variedade de dados que serão usados
<br>
para treinar o modelo de reconhecimento de voz.
<br>
No futuro, planejo, sem adicionar novos falantes, adicionar ruído, etc a fim de aumentar a massa
<br>
de dados.

<br>

## Contribuições...

<br>

Toda e qualquer contribuição será muito bem vinda!

<br>
# Laboratorio-STRE

## Descrição do Projeto
O projeto abordado, visa mostrar o aprendizado da disciplina de Sistemas em Tempo Real e Embarcados (STRE). Com a elaboração dos projetos *"Lab-3"* e *"Lab-4"*.

## Desenvolvimento 
Os exercícios foram desenvolvidos e implementados tanto **fisicamente na protoboard** quanto com a utilização do **Tinkercad**.

### Laboratorios
- **_"LAB-3"_**
  - [Exercício 1](https://www.tinkercad.com/things/jHjXwL7b5Sn) 
  - [Exercício 2](https://www.tinkercad.com/things/fTrES6tgmqU)
  - [Exercício 3](https://youtu.be/7KvGVpiXjso)
- **_"LAB-4"_**
  - [Exercício 1 e 2](https://www.tinkercad.com/things/hyjHiNnYiS5)

### Explicação dos Exercicios
- **LAB-3** 
  - Exercício 1 
  > O exercício solicitava que fosse implementado um LED que pisca-se em intervalos de um segundo. Nós efetuamos esta implementação.
    E adicionalmente, implementamos outros seis LEDs, três deles piscam simulando a estrutura de dados pilha. Onde o primeiro a entrar, neste caso acender, será o último a sair, no nosso caso apagar. E os outros 3 LEDs piscam conforme a estrutura de dados fila, onde o primeiro a acender será o primeiro a apagar.

  - Exercício 2
  >O exercício solicitava que o estado de um botão fosse exibido no monitor serial. Na nossa implementação além de ocorrer o solicitado, quando o estado do botão é igual a apertado, ele acende um LED que por sua vez, altera o valor medido por um sensor de luminosidade, e este por sua vez desativa o buzzer. Resumindo, ao apertar o botão, o estado é impresso no monitor serial, o LED acende e o buzzer desliga.

  - Exercício 3
  > O exercício solicitava a utilização da biblioteca **NILRTOS** para acender e apagar um LED com a utilização de thread. Realizamos a implementação da solicitada, porém com 3 LEDS e 3 threads. Adicionalmente implementamos uma série de prints no monitor serial que mostram claramente, qual trecho do código está sendo executado no momento e por qual thread. Dessa forma, qualquer um que conseguir rodar o código, conseguirá entender o funcionamento das threads.   

- **LAB-4**
  - Exercício 1 e 2
  >O exercício 01 solicitava que fosse construído este circuito e que um alarme sonoro dispara-se sempre que o valor medido pelo sensor de luminosidade fosse inferior a algum valor. Valor este não determinado pelo exercício. O exercício dois, solicitava que fosse exibido no monitor serial o valor medido pelo sensor de luminosidade. Realizamos as implementações em um único circuito e adicionamos um LED que pisca para mostrar a alteração de estados.

#### Colaboradores
|            Nome            |                Email                |    RA    |
|:--------------------------:|:-----------------------------------:|:--------:|
| Flávio Nassim Bittar Filho | flavio.bittar@sempreceub.com        | 21907957 |
| Rafael Abreu Fonseca       | rafael.abreu.fonseca@sempreceub.com | 21700439 |

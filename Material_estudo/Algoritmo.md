## O que é Algoritmo?

Algoritmo é simplesmente uma "receita" para executarmos uma tarefa ou resolver algum problema. E como toda receita, um algoritmo também deve ser finito. Se seguirmos uma receita de bolo corretamente, conseguiremos fazer o bolo. A computação utiliza muito esse recurso.

Embora as vezes não percebemos, utilizamos algoritmos no nosso dia-a-dia e não sabemos. Para a execução de alguma tarefa ou mesmo resolver algum problema, muitas vezes inconscientemente executamos algoritmos. 

### EXEMPLO DE ALGORITMO

**Imagine** o trabalho de um recepcionista de cinema, ele deve conferir os bilhetes e direcionar o cliente para a sala correta. Além disso, se o cliente estiver 30 minutos adiantado o recepcionista deve informar que a sala do filme ainda não está aberta. E quando o cliente estiver 30 minutos atrasado o recepcionista deve informar que a entrada não é mais permitida

Vamos escrever um algoritmo para descrever a atividade do recepcionista:

<u>Algoritmo Recepcionista de Cinema</u>
**Inicio**
1 - Solicitar ao cliente o bilhete do filme.
2 - Conferir a data e o horário do filme no bilhete.
**Se** data/hora atual > data/hora do filme + 30 minutos Então
3 - Informar ao cliente que o tempo limite para entrada foi excedido.
4 - Não permitir a entrada.
**Senão Se** data/hora atual < data/hora do filme - 30 minutos Então
5 - Informar ao cliente que a sala do filme ainda não foi liberada para entrada.
6 - Não permitir a entrada.
**Senão**
7 - Permitir a entrada.
8 - Indicar ao cliente onde fica a sala do filme.
**Fim-Se**
**Fim**

Todas as tarefas executadas pelo computador, são baseadas em Algoritmos. Logo, um algoritmo deve também ser bem definido, pois é uma máquina que o executará. Uma calculadora por exemplo, para executar a operação de multiplicação, executa um algoritmo que calcula somas até um determinado número de vezes. Abaixo, um exemplo do algoritmo de multiplicação. Para facilitar, consideremos que os fatores da multiplicação são positivos.

<u>Algoritmo Multiplicação de números positivos</u>
**Declaração de variáveis**
numero1, numero2, resultado, contador: Inteiro
**Inicio**
ler(numero1)
ler(numero2)
resultado <- 0
contador <- 0
**Enquanto** contador < numero2 **Faça**
resultado <- resultado + numero1
contador <- contador + 1
**Fim-Enquanto**
escrever(resultado)
**Fim**

Este algoritmo pode ser considerado complexo por iniciantes, mas algoritmos deste tipo, utilizando variáveis e controle de fluxo, é muito comum em programação. Se você quer aprender programação, é necessário entende-ló, se não conseguiu, leia-o novamente com mais atenção. Para ajudar, vamos definir algumas coisas importantes sobre o algoritmo:

- **Variável**: é um espaço alocado na memória para armazenar dados. No algoritmo, foram criadas 4 variáveis.
- O símbolo "**<-**" representa uma atribuição de valor a uma variável. Por exemplo, (***resultado <= resultado + numero1\***) atribui à variável *resultado*, o valor da própria variável *resultado*, acrescido do valor da variável *numero1*.
- O comando "**ler(numero1)**", significa que o algoritmo está lendo o que o usuário digita e armazenando na variável *numero1*.
- O comando **Enquanto** é uma estrutura de controle de fluxo do tipo "Estrutura de repetição".
- O comando **escrever(resultado)** exibe na tela o valor da variável *resultado.*

Com o tempo, a leitura e criação de algoritmos passa a ser uma coisa muito simples para um programador. Mas para isso é preciso bastante prática! Então, você pode começar fazendo um exercício, crie algoritmos para as suas tarefas do dia-a-dia a partir do momento em que você acorda. Essa é a melhor forma de aprender a criar algoritmos.




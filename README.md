# Data Science - RNAs - Treinamento Supervisionado

## Exercício

Execute as seguintes tarefas:

### 1) Crie um software que seja programado para ler um arquivo TXT com o seguinte conteúdo:

010 <br/>
101 <br/>
111 <br/>
101 <br/>
101 <br/>
00000Letra A <br/>
 <br/>
111 <br/>
100 <br/>
110 <br/>
100 <br/>
111 <br/>
10000Letra E <br/>
 <br/>
010 <br/>
010 <br/>
010 <br/>
010 <br/>
010 <br/>
11000Letra I <br/>
 <br/>
111 <br/>
101 <br/>
101 <br/>
101 <br/>
111 <br/>
11100Letra O <br/>
 <br/>
101 <br/>
101 <br/>
101 <br/>
101 <br/>
111 <br/>
11110Letra  U <br/>
 <br/>
 <br/>

O conteúdo do arquivo a ser lido (visto acima) possui cinco agrupamentos de dados. 
Cada agrupamento representa uma das vogais. Cada vogal será representada por uma
matriz de cinco linhas por três colunas. A sexta linha de cada agrupamento, após
os dados de entrada para o treinamento, representa a saída desejada para a letra
que será treinada.
 <br/>

### 2) Se julgar necessário, para observar uma implementação do que está sendo solicitado neste exercício, baixe o arquivo TesteRedeNeural.exe (disponível neste repositório). Crie um arquivo de texto e grave nele o conteúdo visto na questão 1 deste exercício. Utilize o software baixado para compreender o funcionamento do treinamento supervisionado. 


### 3) Crie um rede neural para treinamento supervisionado, considerando o conteúdo lido, do arquivo citado, como o mapa de treinamento. O objetivo é atingir o erro médio máximo parametrizado, conforme visto na imagem:

![Drag Racing](./rna_letras_treinamento.png)

### 4) Construa, no mesmo software, uma interface para testar a rede neural após o seu treinamento.

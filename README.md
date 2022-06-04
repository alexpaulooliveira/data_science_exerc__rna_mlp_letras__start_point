# Data Science - RNA MLP

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
os dados de entrada para o treinamento, representará a saída desejada para a letra
que será treinada.


### 2) Crie um rede neural para treinamento supervisionado, considerando o conteúdo lido do arquivo citado como o mapa de treinamento. O objetivo é atingir o erro médio máximo parametrizado na interface à semelhança do que pode ser visto na imagem:

![Drag Racing](./rna_letras_treinamento.png)


### 3) Após concluir o treinamento, crie uma interface para testar a rede neural. 
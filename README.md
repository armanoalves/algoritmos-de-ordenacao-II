# algoritmos-de-ordenacao-II

## Aprendizados

### Aula 01
- Após o teste de mesa realizado nas primeiras aulas, foi construido um código com base nas sequências realizadas no teste de mesa;

- O mesmo sofreu de um problema na condição para rodar o `while` onde parava mesmo sem agrupar todos os componentes da uma lista, já que a dependencia eram de duas a estrutura parava;

- Como solução, foi implementado outras duas estruturas de `while` para adicionar esses componentes restantes dentro da lista não concluida, para dentro da lista final.

### Aula 02

- Expandimos o conceito de “dividir para conquistar”, reutilizando a lógica de ordenar duas listas, e desenvolvemos um algoritmo para ordenar uma única lista;

- Utilizando o recurso das simulações e testes, entendemos o funcionamento de um algoritmo de ordenação muito utilizado no dia-a-dia, o "Merge Sort";

- Após entendermos o fluxo do algoritmo, fizemos a implementação do algoritmo Merge Sort com JavaScript, através da função `mergeSort()` que recebe um array e retorna este array ordenado;

- Estudamos a ferramenta de "recursão", como ela pode ser utilizada no algoritmo Merge Sort e as diferenças dessa ferramenta com relação aos laços de repetição.

### Aula 03 

- Trabalhamos com o conceito de pivô, entendemos como selecionar um elemento pivô no código e como posicionar este elemento em uma lista, comparando valores e contando elementos menores;

- Após posicionar um elemento pivô em um array, desenvolvemos um código em JavaScript que percorre uma lista e separa todos os elementos entre maiores e menores que o pivô, através da função `encontraMenores();`

- A partir do conceito de elemento pivô, entendemos o funcionamento do algoritmo de ordenação quick sort, fazendo mais simulações e testes;

- Após entendermos o algoritmo, implementamos o código utilizando JavaScript e reaproveitando funções e conceitos das aulas anteriores, como a função `trocaLugar()` e a recursão.

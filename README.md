# Separador-de-Amostras
Separador de Amostras desenvolvido para a cadeira de Redes Neurais

## Para utilizar
1. Renomeie o arquivo xlsx com as amostras para _"Entrada.xlsx"_ e a planilha com os dados para _"Original"_.
2. Execute o código de _"SeparadorAmostras.py"_ na mesma pasta em que esta o arquivo _"Entrada.xlsx"_.
3. A saída será um arquivo _"Saida.xlsx"_.

## O arquivo "Saida.xlsx"
O arquivo de saida contém as seguintes planilhas:
* **Original:** Uma cópia da planilha _"Original"_ em _"Entrada.xlsx"_;
* **Grupo 0 e Grupo 1:** Planilhas com os elementos com rótulo 0 e 1, respectivamente;
* **Divisao 0 - Divisao 9:** 10 planilhas com os conjuntos que serão usados para treinamento, validação e teste.

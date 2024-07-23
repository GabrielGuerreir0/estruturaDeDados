# Biblioteca de Vetores em C

## Descrição do Projeto

Este projeto implementa uma biblioteca em C para realizar operações básicas em vetores, incluindo travessia, busca, inserção e exclusão de elementos. O objetivo é fornecer funções úteis para manipulação de vetores de forma eficiente.

## Estrutura do Projeto

O projeto é composto por um arquivo de cabeçalho (`bibliotecaVetores.h`) e um arquivo de implementação (`bibliotecaVetores.c`).

### Arquivo de Cabeçalho (`bibliotecaVetores.h`)

Este arquivo contém as declarações das funções implementadas no arquivo `.c`:

```c
#ifndef bibliotecavetores_h
#define bibliotecavetores_h

void travessiaVetor(int vetor[], int tamanhoAtualVetor);
int buscaElemento(int vetor[], int tamanhoAtualVetor, int valorElemento);
void insereElemento(int vetor[], int tamanhoAtualVetor, int valorElemento, int posicaoInsercao);
int excluirElemento(int vetor[], int tamanhoAtualVetor, int valorElemento);

#endif

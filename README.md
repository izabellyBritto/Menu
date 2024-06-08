# Exercício - Agenda

Este é um programa simples de agenda que permite cadastrar, listar, editar, excluir e ordenar contatos. O programa utiliza uma estrutura (struct) para armazenar informações de cada contato, incluindo código, nome e telefone. Além disso, um vetor do tipo da estrutura é utilizado para armazenar os contatos.

## Instruções

1. **Cadastrar:** Permite cadastrar uma pessoa por vez na agenda.
2. **Listar:** Lista todos os contatos cadastrados na agenda.
3. **Editar:** Permite editar as informações de um contato existente, solicitando o código ou o nome da pessoa a ser editada.
4. **Excluir:** Remove um contato da agenda, garantindo que não haja posições vazias no meio da lista.
5. **Ordenar por nome:** Ordena os contatos por nome, utilizando a função `strcmp(x,y)` da biblioteca string.h.
6. **Sair:** Encerra o programa.

## Implementação

O programa é implementado em linguagem C e cada opção do menu é implementada em uma função separada. Não há uso de variáveis ou vetores globais.

## Estrutura de Dados

O programa utiliza a seguinte estrutura para representar cada contato:

```c
struct Contato {
    int codigo;
    char nome[50];
    char telefone[15];
};


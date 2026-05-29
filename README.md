Este projeto reúne duas implementações utilizando estruturas de dados em C:

    Gerenciador de Inteiros com Lista Encadeada Simples
    Playlist de Música com Lista Circular Duplamente Encadeada

O objetivo é aplicar conceitos de ponteiros, alocação dinâmica e manipulação de listas encadeadas sem utilização de vetores auxiliares.

Integrantes

    Leandro Augusto Krajevski
    Brayan Salles Dombroski

Tecnologias utilizadas

    Linguagem C

Estrutura do Projeto
Atividade 2

Parte 1: Inserção em Posição Específica.

Parte 2: Busca por Valor.

Parte 3: Inverter Lista.

Parte 4: Dividir Lista em Duas.

Playlist: Playlist Circular Duplamente Encadeada.
Parte 1-4 — Lista Encadeada Simples
Explicação

Foi implementada uma lista encadeada simples para armazenar números inteiros dinamicamente.
Estrutura utilizada:

[10] -> [20] -> [30] -> NULL

Cada nó possui:

    um valor inteiro
    um ponteiro para o próximo nó

Funcionalidades
Inserção em posição específica

Permite inserir elementos no início, meio ou final da lista.
Busca por valor

Percorre a lista retornando a posição do valor encontrado.
Inversão da lista

Inverte a ordem dos elementos utilizando apenas ponteiros.
Divisão da lista

Divide a lista em duas partes utilizando a técnica fast/slow pointer.
Liberação de memória

Libera todos os nós utilizando free() para evitar vazamentos de memória.
Playlist — Playlist Circular Duplamente Encadeada
Explicação

Foi implementada uma playlist de músicas inspirada em aplicativos como Spotify utilizando lista circular duplamente encadeada.
Estrutura utilizada:

Cada música possui:

    ponteiro para próxima música
    ponteiro para música anterior

O último nó aponta para o primeiro, mantendo a circularidade.
Funcionalidades
Adicionar músicas

Insere músicas ao final da playlist mantendo a ligação circular.
Navegação bidirecional

Permite avançar ou voltar entre músicas.
Exibição da playlist

Mostra todas as músicas presentes.
Contagem de músicas

Retorna a quantidade total de músicas da playlist.
Controle de percurso

Detecta quando todas as músicas já foram tocadas para evitar loop infinito.
Liberação de memória

Remove todos os nós da playlist utilizando free().
Conclusão

O projeto permitiu aplicar conceitos fundamentais de Estruturas de Dados utilizando linguagem C, principalmente:

    ponteiros
    listas encadeadas
    listas circulares
    alocação dinâmica
    gerenciamento de memória

Além disso, as implementações demonstram como manipular estruturas dinâmicas de forma eficiente sem uso de vetores auxiliares.

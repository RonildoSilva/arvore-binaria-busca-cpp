# Árvores Binárias de Busca em C++

> Implementações de árvore binária de busca, árvore AVL e árvore rubro-negra, com impressão colorida no terminal.

![status](https://img.shields.io/badge/status-concluído-success) ![cpp](https://img.shields.io/badge/C%2B%2B-11-blue)

## Sobre
Trabalho da disciplina de Estrutura de Dados (UFC, 2016). As três estruturas compartilham a classe base `ArvoreBinaria`; `AVL` acrescenta fator de balanceamento e rotações, e `ArvoreRN` acrescenta cor nos nós e as correções de inserção. A impressão usa códigos ANSI para diferenciar nós vermelhos e pretos.

## Stack
- C++11, biblioteca padrão
- Compila com g++ em Linux ou MinGW em Windows

## Estrutura de pastas
```text
No.h / No.cpp                     nó com valor, filhos, pai, balanceamento e cor
ArvoreBinaria.h / .cpp            inserção, busca e remoção da ABB
AVL.h / AVL.cpp                   rotações simples e duplas, verificação de balanceamento
ArvoreRN.h / ArvoreRN.cpp         inserção rubro-negra e recoloração
Impressao.h / Impressao.cpp       impressão hierárquica no terminal
main.cpp                          menu de testes
```

## Como executar
```bash
g++ -std=c++11 *.cpp -o arvores
./arvores
```

## Status
Concluído. Trabalho acadêmico; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com

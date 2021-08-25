# Criando uma aplicação de transferências bancárias com .NET
Criei um algoritmo simples de transferência bancária para exercer o pensamento orientado a objetos, o principal paradigma de programação utilizada no mercado. Nesse projeto aprendi: Como pensar orientado a objetos, como modelar o seu domínio, como utilizar enums.

## Pré-requisitos
- Lógica de programação
- Conhecimento básico em OO
- Conhecimento básico de .NET

## Procedural
- Criar código rapidamente
- Mais difícil para manter (manualmente)
- Pequenos times pequenas aplicações

## Orientada a objetos
- Mais fácil de manter
- Reúso
- Mais fácil e rápido de adicionar funcionalidades
- Em alguns casos, menor performance
- Curva de aprendizado

![class](https://user-images.githubusercontent.com/72028645/130852011-3234cb61-1516-4f52-a13b-4c3377bed95d.png)

## Arrays
- Vetores
- Objetos do mesmo tipo
- Itens são chamados de elementos

>int[] numeros;

Determinar a quantidade:
>int[] numeros = new int[15];

Elementos do vetor:
>int[] numeros = new int[] {0, 1, 2, 3, 4, 5};

## Collections
- Arrays são usados quando o tamanho da coleção é conhecida 
- Quando não sabemos o tamanho ou os elementos que podem ser adicionados/removidos durante a execução usamos as collections
>using System.Collections.Generic;

## List<T>
- É a coleção mais comum é C#, onde T é a classe dos objetos que serão os elementos da lista/coleção
- [Documentação](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)

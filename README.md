# Escrevendo as Classes de um Jogo

Projeto desenvolvido como parte do bootcamp da Digital Innovation One (DIO), focado nos fundamentos da Programação Orientada a Objetos (POO), estruturas de controle e manipulação de variáveis com JavaScript.

---

## Descricao

O objetivo principal deste projeto e aplicar conceitos essenciais de desenvolvimento de software atraves da criacao de uma classe generica responsavel por instanciar herois de aventura. Cada heroi possui atributos especificos e pode executar uma acao de ataque personalizada de acordo com a sua classe/tipo.

---

## Conceitos Aplicados

- Programacao Orientada a Objetos (Classes, Construtores, Instanciacao e Metodos)
- Estruturas Condicionais (switch/case para definicao de acoes)
- Lacos de Repeticao (iteracao sobre colecoes de objetos)
- Tratamento e Normalizacao de Dados (manipulacao de strings com toLowerCase)
- Funcoes e modularizacao

---

## Regras de Negocio

Cada heroi deve conter:
- **Nome**: Nome do personagem
- **Idade**: Idade do personagem
- **Tipo**: Classe do personagem (ex.: mago, guerreiro, monge, ninja)

Comportamento do metodo `atacar()` conforme o tipo:

| Tipo | Descricao do Ataque | Mensagem de Saida |
| :--- | :--- | :--- |
| Mago | magia | `o mago atacou usando magia` |
| Guerreiro | espada | `o guerreiro atacou usando espada` |
| Monge | artes marciais | `o monge atacou usando artes marciais` |
| Ninja | shuriken | `o ninja atacou usando shuriken` |

---

## Estrutura do Projeto

```text
.
├── index.js       # Implementacao da classe Heroi e execucao dos testes
└── README.md      # Documentacao do repositorio

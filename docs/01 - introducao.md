# Introdução à linguagem C

## O que é C

C é uma linguagem de programação criada em 1972 por Dennis Ritchie, nos 
laboratórios Bell. Ela foi desenvolvida originalmente para escrever o 
sistema operacional Unix, e até hoje é uma das linguagens mais influentes 
já criadas — grande parte dos sistemas operacionais, drivers e linguagens 
mais recentes (incluindo o próprio Python) são escritos em C ou fortemente 
inspirados por ela.

## Por que aprender C

Diferente de linguagens de mais alto nível como Python, C trabalha muito 
mais perto do hardware. Isso significa:

- Você lida diretamente com memória (variáveis, ponteiros, alocação manual)
- Não existe um "intérprete" fazendo mágica por trás — o código é compilado 
  direto para instruções que o processador entende
- Erros que Python esconde ou trata automaticamente (como estouro de 
  memória) em C são responsabilidade sua

Isso torna C mais trabalhoso no início, mas ensina como o computador 
realmente funciona por baixo dos panos — um entendimento que ajuda em 
qualquer linguagem depois.

## Diferenças em relação ao Python

| Python | C |
|---|---|
| Interpretado | Compilado |
| Tipagem dinâmica | Tipagem estática (declara o tipo de cada variável) |
| Gerenciamento de memória automático | Gerenciamento manual (malloc/free) |
| Sintaxe mais próxima da linguagem natural | Sintaxe mais próxima do hardware |

## Como este guia está organizado

- `02-conceitos.md` — fundamentos da linguagem (variáveis, tipos, entrada e 
  saída, estruturas de controle)
- `03-exercicios.md` — exercícios práticos resolvidos durante o aprendizado
- `04-referencias.md` — materiais e links usados como apoio
- `exemplos/` — trechos de código comentados

## Referência de apoio

Este guia acompanha o aprendizado feito através do site 
[c-lang-learning](https://c-lang-learning.com), complementado por prática 
e experimentação própria.
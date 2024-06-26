# Guia Básico de Marcação Markdown
Este guia oferece um passo a passo detalhado sobre como utilizar a marcação Markdown para formatação de texto em documentos. Iniciando desde os conceitos básico, como títulos e parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada tópico é acompanhado por uma discrição simples e exemplos práticos em Markdown, permitindo que os usuários aprendam e apliquem rapidamente a marcação Markdown em seus próprios documentos.

## Títulos

São usados para criar diferentes níveis de títulos em documento Markdown.

Exemplos:
# Título 1
## Título 2
## Título 3

## Parágrafos
Simplismente escreva seu texto como parágrafos normais. Não é necessário nenhum tipo de marcação adicional.

Exemplo:
Aqui tenho um parágrafo

## Listas
Permitem criar listas ordenadas ou não ordenadas.

Exemplo:
Lista não ordenada:

* Item 1
* Item 2
* Item 3

Lista ordenada:

1. Primeiro item
2. Primeiro item
3. Primeiro item 


## Links
Criam links para outras páginas na web

Exemplo:

[Texto do link](URL) para criar link.


## Imagens
Inserem imagens em um documento Markdown.

Exemplo:

![Imagem](URL_da_imagem)


## Ênfase
Permitem enfatiar texto, como itálico, negrito, tachado, subscrito e sobrescrito.

Exemplo:

*texto em itálico* ou _texto em itálico_ para itálic

**texto em negrito** ou __texto em negrito_) para negrito

~~Texto em tachado~~

Aqui é um texto <sub> subscrito </sub>

Aqui um texto <sup> sobrescrito </sup>


## Citações em Bloco
São usadas para destacar uma citação ou bloco de texto.

Exemplo:

> Isso é uma citação em bloco.

## Linhas Orizontais
São usadas para criar uma linha horizontal para separar seções do documento.

Exemplo:

---

## Código
Permitem inserir blocos de código ou destacar código dentro do texto.

Exemplo:

use crases (\`) para inserir código `inline`.

```
idade = 18
print(f"A idade é {idade}")
```

## Tabelas
Criam tabelas organizadas em colunas e linhas.

Exemplo:

|cabeçalho 1| cabeçalho 2|
|-----------|------------|
|Dado 1     |Dado 2      |
|Dado 3     |Dado 4      |



## Listas de Tarefas
Criam listas de tarefas que podem ser marcadas como concluídas ou pendentes.

Exemplos:

- [x] Tarefa Concluída
- [ ] Tarefa Pendente

## Referências
Permitem adicionar notas de rodapé para fornecer maisinformações sobre conteúdo do documento.

Exemplo:

Aqui é um exemplo demarcação em rodapé [^1].

A aula é com o Ricardo[^2].

 [^1]: Rodapé: conteúdo inferior do documento.
 [^2]: Ricardo: Professor da turma de Git.


## Notas de Rodapé
São usadas para adicionar informações adicionais ou explicativas ao final de um documento.

Exemplo:

Aqui é um exemplo demarcação em rodapé [^1].

A aula é com o Ricardo[^2].

 [^1]: Rodapé: conteúdo inferior do documento.
 [^2]: Ricardo: Professor da turma de Git.

## Alertas
São usados para destacar informações importantes, como notas, aviso ou mensagem.

Exemplo: 

> **note**
> Esta é a nota

> [!NOTE]
> Destaca informações que os usuários devem levar em consideração, mesmo durante a leitura superficial.

>  [!IMPORTANT]
> Informações cruciais necessárias para osucesso dos usuários.

> [!WARNING]
> Conteúdo que exige atenção imediata do usuário devido a riscos em potencias.

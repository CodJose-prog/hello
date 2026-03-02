# Jornada em Golang

Este repositorio registra minha evolucao nos estudos de Go (Golang), com versoes que mostram o que foi aprendido em cada atualizacao.

## Como executar

```bash
go run hello.go
```

## Historico de versoes

### v1.0 - Primeiro programa em Go (Ola Mundo)
- Estrutura basica de um programa Go (`package main`, `func main()`).
- Uso do pacote `fmt`.
- Primeira execucao com `go run hello.go`.

Trecho de codigo da versao:

```go
package main

import "fmt"

func main() {
	fmt.Println("Ola Mundo! Estou estudando a linguagem GO.")
}
```

### v1.1 - Tipos de variaveis e saida no terminal
- Introducao de variaveis no codigo (`nome`, `idade`, `versao`).
- Pratica com inferencia de tipo usando `:=`.
- Impressao de dados com `fmt.Println`.

Trecho de codigo da versao:

```go
nome := "Jose Manoel"
idade := 19
versao := 1.1
fmt.Println("Ola, sr.", nome, "sua idade e", idade, "anos.")
fmt.Println("Este programa esta na versao", versao)
```

## Regra de atualizacao do README

A cada nova modificacao do codigo, este README deve ser atualizado com:
- Numero da versao.
- Tema estudado na versao.
- Resumo objetivo do que foi implementado.
- Trecho de codigo relacionado ao que foi trabalhado na versao.

Se voce informar o que foi trabalhado, eu atualizo com base nessa informacao.
Se nao informar, eu analiso o codigo e atualizo automaticamente.

Meu portfolio: [https://josemanoeldev.vercel.app](https://josemanoeldev.vercel.app)

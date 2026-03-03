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

### v1.2 - Diferenca entre `fmt.Scanf` e `fmt.Scan`
- Estudo de leitura de dados no terminal com `fmt`.
- `fmt.Scan` le valores separados por espaco e quebra de linha, sem mascara de formato.
- `fmt.Scanf` le usando uma mascara (exemplo: `%d`, `%s`, `%f`), exigindo formato mais controlado.
- No codigo atual, o comando do menu foi lido com `fmt.Scan`.

Trecho de codigo da versao:

```go
var comando int
fmt.Scan(&comando)
fmt.Println("O comando escolhido foi", comando)

var idade int
fmt.Scanf("%d", &idade)
```

### v1.3 - Controle de fluxo com `if`
- Implementacao de decisao no programa com `if`, `else if` e `else`.
- Tratamento de comandos digitados no menu (`1`, `2`, `0` e opcao invalida).
- Pratica de logica condicional para controlar o comportamento da aplicacao.

Trecho de codigo da versao:

```go
if comando == 1 {
	fmt.Println("Monitoramento iniciado...")
} else if comando == 2 {
	fmt.Println("Exibindo Logs...")
} else if comando == 0 {
	fmt.Println("Saindo do programa...")
} else {
	fmt.Println("Comando desconhecido")
}
```

### v1.4 - Controle de fluxo com `switch`
- Refatoracao da logica condicional de `if/else if/else` para `switch`.
- Codigo mais organizado para tratar multiplas opcoes de menu.
- Uso do `default` para lidar com comandos invalidos.

Trecho de codigo da versao:

```go
switch comando {
case 1:
	fmt.Println("Monitoramento iniciado...")
case 2:
	fmt.Println("Exibindo Logs...")
case 0:
	fmt.Println("Saindo do programa...")
default:
	fmt.Println("Comando desconhecido")
}
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

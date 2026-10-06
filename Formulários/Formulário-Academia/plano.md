# Formulário de Contato — Academia

## Cenário

A academia **Corpo em Movimento** quer permitir que visitantes do site enviem dúvidas sobre planos, horários e aulas experimentais.

## Objetivo

Criar um formulário de contato simples, semântico e acessível.

## Público-alvo

Pessoas interessadas em se matricular na academia, com foco principalmente em usuários que acessam pelo celular.

## Campos do formulário

| Campo | Elemento | Tipo | Obrigatório | Opções |
|---|---|---|---|---|
| Nome completo | `input` | `text` | Sim | — |
| E-mail | `input` | `email` | Sim | — |
| Telefone | `input` | `tel` | Não | — |
| Assunto | `select` | — | Sim | Planos, Horários, Aula experimental, Outro |
| Mensagem | `textarea` | — | Sim | — |

## Requisitos

- Utilizar a tag `<form>` com:
  - `action="#"`
  - `method="post"`
- Cada campo deve possuir um `<label>` associado por meio dos atributos `for` e `id`.
- Agrupar campos relacionados utilizando `<fieldset>` e `<legend>`.
- Finalizar o formulário com:

```html
<button type="submit">Enviar</button>
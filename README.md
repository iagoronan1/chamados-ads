# chamados-ads
IAGO RONAN ALMINO OLIVEIRA
Matrícula: 2025012453

## Objetivo

Desenvolver a estrutura inicial de uma API de chamados de suporte utilizando Python e Flask, como parte da atividade da Semana 01.

Nesta etapa, foi implementada a rota inicial da API, responsável por retornar uma mensagem indicando que o serviço está em funcionamento.

## Tecnologias utilizadas

- Python
- Flask
- uv

## Instalação das dependências

Com o projeto clonado e o uv instalado, execute:

```bash
uv sync --locked
```

## Como executar a aplicação

Execute o seguinte comando no terminal:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Acesso à API

Com a aplicação em execução, acesse:

http://localhost:5000/

## Resposta esperada

Status HTTP: 200 OK

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

## Rota implementada

| Método | Rota | Descrição |
|---|---|---|
| GET | / | Retorna mensagem de funcionamento da API |

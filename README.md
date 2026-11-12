# Calculadora Web (Python, Flask, HTML e JavaScript)

**Autora:** Bruna Medeiros

Este projeto consiste em uma calculadora web desenvolvida utilizando Python, Flask, HTML e JavaScript.

A aplicação permite realizar quatro operações matemáticas: **soma, subtração, multiplicação e divisão**, cada uma disponível em sua própria página.

## Tecnologias utilizadas

- Python
- Flask
- HTML
- JavaScript
- Git e GitHub

## Requisitos

- Python 3 instalado
- VS Code
- Git instalado
- Flask instalado

## Estrutura do projeto

```text
calculadora_bru/
│
├── app.py
├── operacoes.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   ├── soma.html
│   ├── subtracao.html
│   ├── multiplicacao.html
│   └── divisao.html
│
└── static/
    └── script.js
```

## Clonando o projeto

Para baixar o projeto, abra o terminal e execute:

```bash
git clone https://github.com/Bruna-mdd/calculadora.git
```

Entre na pasta do projeto:

```bash
cd calculadora
```

## Instalando o Flask

Execute o comando:

```bash
python -m pip install -r requirements.txt
```

## Executando a aplicação

Na pasta do projeto, execute:

```bash
python app.py
```

Quando o servidor iniciar, abra o navegador e acesse:

```text
http://127.0.0.1:5000
```

## Funcionalidades

- Adição de dois números.
- Subtração de dois números.
- Multiplicação de dois números.
- Divisão de dois números.
- Verificação para impedir divisão por zero.
- Navegação entre as páginas por meio de um menu.

## Autora

Bruna Medeiros

Projeto desenvolvido para fins acadêmicos.
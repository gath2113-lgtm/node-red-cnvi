# Projeto Node-RED: Fundamentos e Fluxos Práticos (CNVI)

Este repositório contém os exercícios e fluxos desenvolvidos para a disciplina **CNVI**, focados no aprendizado prático do **Node-RED** com base na documentação e tutoriais oficiais.

---

## 📂 Estrutura do Projeto
- **`README.md`**: Guia explicativo dos conteúdos do repositório.
- **`flows/`**: Arquivos em formato JSON contendo a lógica dos fluxos implementados.

---

## 📋 Lista de Fluxos Desenvolvidos

| Arquivo / Fluxo | Conceito Estudado | Descrição Funcional |
|---|---|---|
| `01-hello-world.json` | Primeiro Fluxo | Envio de mensagem simples ("Olá, Node-RED!") via Inject para o painel Debug. |
| `02-inject-timestamp-e-repeticao.json` | Timestamps | Disparo manual de carimbo de data e hora para monitoramento no Debug. |
| `03-function-node.json` | Manipulação de String | Função em JavaScript para converter mensagens de entrada em maiúsculas. |
| `04-change-node.json` | Alteração de Payload | Definição direta de valores numéricos na propriedade `msg.payload`. |
| `05-switch-node.json` | Roteamento Condicional | Redirecionamento de dados baseado em comparações numéricas (`< 30` e `> 70`). |
| `06-template-node.json` | Formatação Mustache | Uso do nó Template para criar saídas dinâmicas formatadas. |
| `07-delay-node.json` | Controle do Tempo | Aplicação de pausa/delay temporizado na passagem do fluxo. |
| `08-http-endpoint.json` | API HTTP | Criação de endpoint GET simples via HTTP In. |
| `09-json-parse.json` | Parser JSON | Processamento e conversão de dados no formato JSON. |
| `10-contexto-contador.json` | Contexto de Fluxo | Implementação de contador com armazenamento persistente em `flow`. |
| `11-split-e-join.json` | Manipulação de Arrays | Divisão e reconstrução de sequências de dados (`split`/`join`). |

---

## ⚙️ Como Rodar os Fluxos

1. Certifique-se de ter o **Node.js** e o **Node-RED** instalados globalmente.
2. Inicie o ambiente executando o comando `node-red` no terminal.
3. Acesse a interface web em `http://127.0.0.1:1880`.
4. No menu lateral (canto superior direito), vá em **Importar** e escolha os arquivos `.json` presentes na pasta do projeto.

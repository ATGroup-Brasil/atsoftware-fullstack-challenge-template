# Desafio de Programação Full-Stack: React + Node.js + TypeScript

Este repositório contém um setup inicial para um projeto full-stack utilizando React, Node.js e TypeScript. O objetivo deste desafio é desenvolver um CRUD completo para máquinas industriais.

## Estrutura do Projeto

### Front-End

O front-end do projeto está localizado na pasta `/front-end` e foi configurado utilizando Vite. Para mais detalhes sobre Vite, consulte o [guia oficial](https://vitejs.dev/guide/).

### Back-End

O back-end do projeto está localizado na pasta `/back-end` e foi configurado utilizando TypeScript. Para mais detalhes sobre como iniciar um projeto com TypeScript, consulte o [tutorial da DigitalOcean](https://www.digitalocean.com/community/tutorials/typescript-new-project).

## Desafio

### API

A API deve conter as seguintes rotas para gerenciamento de máquinas:

- **GET /machine**: Recuperar uma lista de todas as máquinas.
- **GET /machine/:machineId**: Recuperar detalhes de uma máquina específica pelo ID.
- **POST /machine**: Criar uma nova máquina.
- **PUT /machine/:machineId**: Atualizar os dados de uma máquina existente pelo ID.

### Interface de Usuário

A interface deve permitir as seguintes funcionalidades relacionadas a máquinas:

- **Página de Criação**: Formulário para adicionar uma nova máquina.
- **Página de Listagem**: Exibir todas as máquinas cadastradas.
- **Página de Edição**: Formulário para editar os dados de uma máquina existente.
- **Botão de Deleção**: Função para remover uma máquina da lista.

## Requisitos

### Obrigatório

- Utilize os templates fornecidos nas pastas `/front-end` e `/back-end`.
- Desenvolva o projeto utilizando React, Node.js, Express e TypeScript.

### Opcional

- Adicione quaisquer bibliotecas ou ferramentas adicionais que considere úteis para a melhoria do projeto.
- Além dos requisitos obrigatórios, você está livre para escolher as bibliotecas que irá utilizar. Faça essa escolha com base nas tecnologias que você já tem experiência.

## Referências
- React https://react.dev/
- Vite https://vitejs.dev/
- Node https://nodejs.org/docs/latest/api/documentation.html
- Express https://expressjs.com/pt-br/
- Typescript https://www.typescriptlang.org/docs/
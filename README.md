# Desafio Técnico - Mini Sistema de Controle Financeiro (Angular)

## Objetivo
Desenvolver um mini sistema de controle financeiro para gerenciar contas de entrada e saída utilizando **Angular**. O candidato deve demonstrar habilidades em desenvolvimento front-end, boas práticas de codificação, e criação de uma interface de usuário (UI) intuitiva.

## Requisitos do Projeto:

### 1. Cadastro de Transações
- Deve ser possível cadastrar transações financeiras com as seguintes informações:
  - Tipo de transação: Entrada ou Saída
  - Descrição da transação
  - Valor
  - Data

### 2. Listagem de Transações
- Exibir uma lista de todas as transações cadastradas, com as seguintes colunas:
  - Tipo (Entrada ou Saída)
  - Descrição
  - Valor
  - Data

### 3. Resumo Financeiro
- Mostrar o saldo total atual (diferença entre entradas e saídas).
- Exibir o total de entradas e o total de saídas separadamente.

### 4. Funcionalidades Extras
- Filtro por tipo de transação (Entrada ou Saída).
- Ordenação das transações por data ou valor.

## Requisitos Técnicos:

- **Framework**: Utilizar **Angular** (versão 11 ou superior).
- **Roteamento**: Implementar uma estrutura de rotas para navegação, por exemplo:
  - Página de Cadastro de Transações
  - Página de Listagem de Transações
  - Página de Resumo Financeiro
- **Estilização**: Utilizar **CSS** ou **Sass** (preferencialmente com **Angular Material** ou **Bootstrap** para estilização de componentes).
- **Validação de Formulário**: Implementar validações nos formulários utilizando os recursos do **Reactive Forms** do Angular (ex. campos obrigatórios, valores numéricos para o valor da transação).
- **Persistência de Dados**: Simular a persistência dos dados utilizando **LocalStorage** ou **SessionStorage**.
- **Responsividade**: A interface deve ser responsiva, adaptando-se a diferentes tamanhos de tela.

## Critérios de Avaliação:

- Qualidade do código: Organização, uso de boas práticas, e clareza.
- Usabilidade da interface: Simplicidade, clareza, e facilidade de uso.
- Validações de dados e tratamento de erros.
- Utilização de componentes e serviços de forma reutilizável.
- Estrutura de rotas organizada.
- Responsividade da aplicação.
- Documentação do projeto (README explicando como rodar o projeto e a estrutura do código).

## Diferenciais (não obrigatórios):

- Uso de **TypeScript** avançado (Interfaces, Enums, Generics).
- Boas práticas de acessibilidade.

## Entrega:
O candidato deve disponibilizar o código em um repositório público no GitHub e incluir instruções de como rodar o projeto localmente.

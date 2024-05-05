# API de Banco Digital
Este README fornece informações importantes sobre o projeto, incluindo uma visão geral, instruções de instalação e uso, além de detalhes sobre as principais funcionalidades.

## Visão Geral
A API foi desenvolvido com o objetivo de oferecer aos clientes uma experiência bancária moderna e eficiente. Ele permite que os usuários realizem diversas operações, como consultas de saldo, transferências, pagamentos de contas e muito mais. O aplicativo é fácil de usar e foi projetado com foco na segurança dos dados dos clientes.

## Funcionalidades
- Listar Contas Bancárias: Endpoint para listar todas as contas bancárias existentes.
- Criar Conta Bancária: Endpoint para criar uma nova conta bancária.
- Atualizar Dados do Usuário da Conta Bancária: Endpoint para atualizar os dados do usuário de uma conta bancária.
- Excluir Conta Bancária: Endpoint para excluir uma conta bancária existente.
- Depositar: Endpoint para realizar um depósito em uma conta bancária.
- Sacar: Endpoint para realizar um saque em uma conta bancária.
- Transferir: Endpoint para realizar uma transferência entre contas bancárias.
- Saldo: Endpoint para consultar o saldo de uma conta bancária.
- Extrato: Endpoint para listar as transações realizadas de uma conta específica.

## Como Usar
### Instalação
### Clone este repositório:

### Instale as dependências:
- npm install
- Express.js
- Nodemon

## Endpoints
- Listar Contas Bancárias: GET /contas?senha_banco=<senha_do_banco>
- Criar Conta Bancária: POST /contas
- Atualizar Dados do Usuário da Conta Bancária: PUT /contas/:numeroConta/usuario
- Excluir Conta Bancária: DELETE /contas/:numeroConta
- Depositar: POST /transacoes/depositar
- Sacar: POST /transacoes/sacar
- Transferir: POST /transacoes/transferir
- Saldo: GET /contas/saldo?numero_conta=<numero_conta>&senha=<senha>
- Extrato: GET /contas/extrato?numero_conta=<numero_conta>&senha=<senha>

## Requisitos
Node.js
npm (Node Package Manager)

## Acesse as Screensshot do projeto
https://postimg.cc/gallery/hJKhGBF

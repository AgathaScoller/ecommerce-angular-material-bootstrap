E-commerce Angular - Integração Material Design e Bootstrap
Este repositório contém a implementação de uma interface de loja virtual desenvolvida com o framework Angular. O projeto integra o Angular Material para componentes estruturais e o Bootstrap para o sistema de grelha e componentes de formulário, conforme os requisitos da atividade de desenvolvimento de interfaces.

Tecnologias e Dependências
Framework: Angular (v16 ou superior)

Linguagem: TypeScript (Orientação a Objetos)

Estilização e UI:

Angular Material: Utilizado em MatToolbar, MatCard e MatGridList.

Bootstrap 5: Utilizado para o layout responsivo e estilização da tela de login.

Gestão de Versões: Git/GitHub.

Estrutura do Projeto
A aplicação está dividida em componentes modulares para garantir a manutenibilidade:

Menu: Cabeçalho com navegação utilizando mat-toolbar.

Início: Vitrine de produtos organizada em grelha com cartões informativos.

Login: Área de autenticação com formulário formatado via Bootstrap.

Rodapé: Secção informativa final com estilização CSS personalizada.

Configuração do Ambiente
Para replicar o ambiente de desenvolvimento, verifique as referências no ficheiro angular.json:

Styles:

node_modules/bootstrap/dist/css/bootstrap.css

@angular/material/prebuilt-themes/indigo-pink.css

Scripts:

node_modules/bootstrap/dist/js/bootstrap.js

Instruções de Execução
Instale as dependências do projeto:

Bash
npm install
Inicie o servidor de desenvolvimento:

Bash
ng serve
Aceda à aplicação via navegador no endereço:
http://localhost:4200/

Requisitos Técnicos Implementados
Definição de classes e métodos em TypeScript.

Configuração de rotas para navegação entre páginas.

Injeção de módulos do Angular Material no app.module.ts.

Implementação de design responsivo.

Este documento serve como registo da entrega da atividade prática de Frameworks com consumo de API.

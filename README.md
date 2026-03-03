**E-commerce Angular - Integração Material Design e Bootstrap**

Este repositório contém a implementação de uma interface de loja virtual desenvolvida com o framework Angular. O projeto foca na integração entre componentes do Angular Material e o sistema de estilização do Bootstrap 5, atendendo aos requisitos de arquitetura de componentes e SPA (Single Page Application).

Tecnologias e Dependências
Framework: Angular v16+

Linguagem: TypeScript

Bibliotecas de UI: Angular Material & Bootstrap 5

Estrutura de Componentes
O projeto foi modularizado para separar as responsabilidades da interface conforme a tabela abaixo:

Componente	Função	Biblioteca Principal
Menu	Navegação superior e logótipo	Angular Material (mat-toolbar)
Início	Vitrine de produtos e banners promocionais	Material Cards & Bootstrap Carousel
Login	Interface de autenticação de utilizador	Bootstrap Forms
Rodapé	Informações institucionais e créditos	CSS Customizado
Configuração do Ambiente
Assegure que as dependências de estilo e scripts estão devidamente mapeadas no ficheiro angular.json para o correto funcionamento das bibliotecas externas:

JSON
"styles": [
  "node_modules/bootstrap/dist/css/bootstrap.css",
  "@angular/material/prebuilt-themes/indigo-pink.css",
  "src/styles.css"
],
"scripts": [
  "node_modules/bootstrap/dist/js/bootstrap.js"
]
Instruções de Instalação e Execução
Para configurar o ambiente localmente, execute os seguintes comandos no terminal:

1. Instalação de dependências:

Bash
npm install
2. Inicialização do servidor de desenvolvimento:

Bash
ng serve
3. Acesso à aplicação:

Plaintext
URL: http://localhost:4200/
Requisitos Técnicos Implementados
TypeScript: Utilização de tipagem estática, definição de classes, construtores e métodos para controlo da lógica dos componentes.

Modularização: Configuração do ficheiro app.module.ts com a importação de módulos específicos (MatButtonModule, MatCardModule, MatInputModule).

Roteamento: Implementação do ficheiro app-routing.module.ts para gestão de navegação entre as páginas de Início e Login.

Layout Responsivo: Uso do sistema de grelha (Grid System) para adaptação da interface a diferentes dispositivos.

Este projeto foi desenvolvido como parte da atividade prática de Frameworks com Consumo de API.

Documentação do Sistema: E-commerce LojaGames
1. Documento de Visão do Negócio
Finalidade
Este sistema tem como objetivo prover uma interface funcional e responsiva para uma loja virtual de jogos, servindo como base para estudos de integração de frameworks front-end.

Escopo
O projeto abrange o desenvolvimento do layout da página inicial (vitrine) e da página de autenticação (login), utilizando Angular, Angular Material e Bootstrap. Não contempla, nesta etapa, integração com banco de dados ou finalização de compra.

Visão Geral
Uma Single Page Application (SPA) que prioriza a velocidade de navegação e a experiência do usuário através de componentes modulares.

Visão Geral do Produto
O produto consiste em uma interface web composta por:

Menu de navegação superior.

Banner promocional.

Grade de produtos com preços e botões de compra.

Formulário de acesso para usuários cadastrados.

Rodapé institucional.

Posicionamento no Mercado
Focado no setor de entretenimento digital (games), oferecendo uma interface moderna que segue os padrões visuais das grandes lojas do segmento.

Descrição da Equipe e Clientes
Desenvolvedora: Agatha Scoller.

Clientes: Entusiastas de jogos eletrônicos que buscam praticidade na visualização de catálogos.

Alternativas e Concorrências
Grandes plataformas como Steam, Epic Games e Nuuvem. O diferencial deste projeto é a arquitetura leve baseada em componentes reutilizáveis.

Restrições
Necessidade de conexão com a internet para carregar bibliotecas externas via CDN (se aplicável).

Compatibilidade limitada a navegadores modernos que suportam ECMAScript 6.

Requisitos do Produto
RF01: O sistema deve listar produtos em formato de cards.

RF02: O sistema deve permitir a navegação entre Home e Login sem recarregar a página.

RNF01: A interface deve ser responsiva (Bootstrap).

RNF02: O tempo de resposta na troca de rotas deve ser inferior a 1 segundo.

2. Modelagem de Caso de Uso
A modelagem de caso de uso descreve o comportamento do sistema sob o ponto de vista do usuário.

Itens da Modelagem:
Atores:

Usuário/Cliente: Pessoa que acessa o site para visualizar o catálogo.

Visitante: Pessoa que acessa a área de login para autenticação.

Cenários (Use Cases):

UC01 - Visualizar Vitrine: O Ator acessa a página inicial e percorre a lista de jogos disponíveis.

UC02 - Acessar Área de Login: O Ator clica no link de navegação e é redirecionado para o formulário de entrada.

UC03 - Realizar Compra (Simulação): O Ator interage com o botão "Comprar" no card do produto.

Comunicação:

A ligação ocorre via interface visual (UI), onde cliques em botões e links disparam as rotas do Angular para os respectivos componentes.

3. Definições, Acrônimos e Abreviações
SPA: Single Page Application (Aplicação de Página Única).

UI: User Interface (Interface do Usuário).

Componente: Unidade básica de construção no Angular (HTML + CSS + TS).

Route: Caminho na URL que define qual componente será exibido.

4. Referências
Material Digital SENAI: Framework com Consumo de API.

Documentação Angular: angular.io

Documentação Bootstrap: getbootstrap.com

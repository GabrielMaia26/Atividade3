# Atividade3
Plataforma Web para ONGs – Entrega III
JavaScript Avançado • SPA • Manipulação do DOM • Validação • Templates

Este repositório contém a implementação da Entrega III da disciplina de Experiência Prática em Desenvolvimento Web.
Nesta etapa, o projeto evolui de páginas estáticas HTML/CSS para uma aplicação dinâmica usando JavaScript avançado, com manipulação do DOM, templates, SPA e validações profissionais.
Objetivos da Entrega

A Entrega III tem como foco:

Transformar o site estático da Entrega I e II em uma aplicação dinâmica.

Utilizar JavaScript avançado para criar interações reais.

Implementar um mini sistema SPA (Single Page Application).

Criar e utilizar templates JavaScript para componentes e seções.

Aplicar validação completa de formulários com feedback visual.

Organizar o código JS de forma modular e escalável.
Funcionalidades Implementadas
✔ 1. SPA – Single Page Application

Navegação dinâmica sem recarregar a página.

Rotas gerenciadas via hash routing (/#home, /#projetos, /#cadastro).

Conteúdo das páginas carregado via JavaScript.

✔ 2. Sistema de Templates via JavaScript

Templates armazenados em arquivos JS dentro da pasta /js/templates/.

O conteúdo é renderizado dinamicamente no container principal da SPA.

Suporte a:

Templates de páginas

Templates de componentes (cards, modais, alerts)

✔ 3. Validação Completa de Formulários

Inclui:

Verificação de campos obrigatórios

Máscaras 

Mensagens de erro

Marcação visual de campos inválidos

Sistema de validação modular em /js/validations/

✔ 4. Manipulação do DOM

Criação e remoção de elementos

Alteração de classes e atributos

Geração de listas e cards de forma dinâmica

Sistema de feedback com alerts e toasts

✔ 5. Armazenamento Local

Armazena projetos ou cadastros no localStorage

Permite carregar dados mesmo após recarregar a página
Estrutura de Pastas do Projeto
/assets
   /img
/css
   design-system.css
   layout.css
   components.css
   reset.css
/js
   /router
       router.js
   /templates
       homeTemplate.js
       projetosTemplate.js
       cadastroTemplate.js
   /validations
       formValidation.js
   app.js
   main.js
index.html
README.md
Descrição:

index.html – ponto de entrada da aplicação.

app.js – inicialização da SPA.

router.js – controla rotas e troca de páginas.

templates/ – contém todas as “páginas” renderizadas dinamicamente.

validations/ – regras de validação e mensagens.

main.js – scripts gerais.

css/ – sistema de estilos modular (da Entrega II).

assets/img – imagens utilizadas no projeto.



cd plataforma-ongs


Abra o arquivo index.html no navegador:

Clique duas vezes nele
ou

Inicie um servidor local opcional:

npx serve .


Navegue pelos menus — a SPA controla a troca de páginas automaticamente.

Tecnologias Utilizadas

HTML5

CSS3

Design System

Grid e Flexbox

Responsividade com 5 breakpoints

JavaScript Avançado

DOM

SPA simples

Templates

Eventos

Validação

Renderização dinâmica

LocalStorage

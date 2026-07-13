# aplicacao-de-tarefas
Aqui está o conteúdo completo e estruturado para o arquivo README.md do seu projeto.
📝 Gerenciador de Tarefas (Task Manager)
Um aplicativo web simples e funcional para gerenciamento de tarefas diárias, desenvolvido em React utilizando componentes funcionais, gerenciamento de estado global com Context API e navegação dinâmica com React Router.
🎯 Propósito do Projeto
Este projeto foi criado com fins didáticos para demonstrar a integração de conceitos fundamentais do ecossistema React em uma única aplicação Single Page Application (SPA). O foco principal é mostrar como:
Gerenciar o estado global de forma limpa usando Context API (createContext, useContext).
Persistir dados no navegador utilizando o LocalStorage.
Criar um fluxo de navegação entre páginas sem recarregar o navegador usando React Router DOM.
Realizar operações completas de CRUD (Criar, Ler, Atualizar e Deletar tarefas).
🚀 Funcionalidades
Visualizar Tarefas: Listagem de todas as tarefas cadastradas.
Criar Tarefa: Formulário para adicionar um novo título e descrição.
Editar Tarefa: Rota dinâmica para atualizar informações de uma tarefa existente.
Excluir Tarefa: Remoção rápida de itens da lista.
Alternar Status: Marcar e desmarcar tarefas como concluídas usando checkboxes.
Persistência: As tarefas não somem ao atualizar a página (salvas no LocalStorage).
🛠️ Tecnologias Utilizadas
React (Componentes Funcionais e Hooks: useState, useEffect)
React Context API (Compartilhamento de estado global)
React Router DOM (Gerenciamento de rotas e parâmetros de URL)
HTML5 / CSS3 (Estruturação e estilização)
💻 Como Executar o Projeto
Como este código está estruturado em um único script que consome as bibliotecas globalmente (geralmente via CDN em sistemas como JSFiddle, CodePen ou em um arquivo HTML simples), você pode executá-lo de duas formas:
Opção 1: Execução Direta (Arquivo HTML Único)
Crie um arquivo chamado index.html no seu computador.
Monte a estrutura básica do HTML contendo uma <div id="root"></div>.
Importe os scripts do React, ReactDOM e ReactRouterDOM via CDN no <head>.
Cole o código JavaScript deste repositório dentro de uma tag <script type="text/javascript"> (ou vincule a um arquivo .js).
Abra o arquivo index.html diretamente em qualquer navegador web.
Opção 2: Em um Ambiente Local Node.js (Vite / CRA)
Se desejar converter este projeto para uma estrutura modular profissional:
Instale as dependências no seu projeto Node:
bash
npm install react react-dom react-router-dom
Use o código com cuidado.
Divida o código movendo o TaskProvider para um arquivo de contexto separado.
Separe os componentes Home, AddTask e EditTask em uma pasta /pages.
Importe os hooks diretamente do topo dos arquivos (ex: import { useState } from 'react';).
Execute o servidor de desenvolvimento local:
bash
npm run dev

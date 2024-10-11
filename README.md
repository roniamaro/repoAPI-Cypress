# repoAPI-Cypress

Pré requisitos:
  NodeJS instalado
  VSCode
  GitBash
1 - Criar projeto
  npm init -y
2 - Instalar Cypress
  npm install cypress
3 - Iniciar Cypress para configurar
  npx cypress open
  Irá abrir um navegador com o Cypress rodando;
    link: 
  Clique em E2E Testing > "not configured" > Continue > Chrome;
4 - Criar arquivo de testes
  No VSCode:
    pasta cypress > criar uma pasta "e2e";
    todos os testes ficarão dentro da pasta "e2e";
    pasta "e2e" > criar os arquivos das funcionalidades que serão testadas;
    arquivo "listar-dispositivos.cy.js";
5 - Criar cenários
  No VSCode:
    arquivo "listar-dispositivos.cy.js";
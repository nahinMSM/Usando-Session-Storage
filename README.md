# Projeto: Compartilhamento de dados entre páginas usando Session Storage

Este projeto consiste em duas páginas HTML interligadas, onde é possível armazenar e compartilhar dados entre elas utilizando a funcionalidade de armazenamento local do navegador, conhecida como Session Storage.

## Funcionalidades:

1. **Layout 1 (index.html):**
   - Exibe um título "Layout 1".
   - Contém um campo de entrada de texto e um botão.
   - Ao clicar no botão "Salvar valor na session storage", o texto inserido no campo de entrada é armazenado na session storage do navegador.
   - Fornece um link para acessar a página 2.

2. **Layout 2 (pg2.html):**
   - Apresenta um título "Page 2".
   - Possui um botão "Exibir o valor da session storage" e um campo de texto.
   - Ao clicar no botão, o valor armazenado na session storage (que foi definido na primeira página) é exibido no campo de texto.

## Utilização:

1. Abra o arquivo `index.html` em um navegador da web.
2. Insira um valor no campo de texto e clique no botão "Salvar valor na session storage".
3. Em seguida, clique no link "Abrir Layout 2" para acessar a segunda página.
4. Na segunda página, clique no botão "Exibir o valor da session storage" para visualizar o valor armazenado na session storage, o qual foi compartilhado da primeira página.

Este projeto é útil para demonstrar como é possível compartilhar dados entre diferentes páginas da web utilizando o armazenamento local do navegador, proporcionando uma experiência mais integrada para o usuário.

Projeto de Catálogo de Filmes com React
Este projeto é um catálogo de filmes criado com React, utilizando a API do TMDB (The Movie Database) para obter informações sobre filmes. O projeto faz uso de hooks e React Router para gerenciar o estado e a navegação entre páginas. A estrutura do projeto foi inicializada com Vite, que proporciona um ambiente de desenvolvimento rápido e eficiente.



https://github.com/WesleyBert/FilmeFlix/assets/90710910/d9b39ad3-1733-4062-84c6-f6984f2afade



Funcionalidades 
Listagem de filmes populares: Exibe uma lista de filmes populares obtidos da API do TMDB.
Detalhes do filme: Ao clicar em um filme na lista, são exibidos detalhes adicionais sobre o filme.
Navegação entre páginas: Uso do React Router para navegar entre a página principal e a página de detalhes do filme.
Pesquisa de filmes: Permite buscar filmes específicos por título.
Interface responsiva: Layout adaptado para diferentes tamanhos de tela.
Tecnologias Utilizadas
React: Biblioteca JavaScript para construção de interfaces de usuário.
Vite: Ferramenta de build e servidor de desenvolvimento rápido.
TMDB API: API utilizada para obter dados sobre filmes.
Hooks do React: Utilizados para gerenciar o estado e efeitos colaterais.
React Router: Biblioteca para roteamento no React.
Pré-requisitos
Node.js instalado (versão 14 ou superior)
NPM ou Yarn instalado
Instalação
Clone o repositório:
bash
Copiar código
git clone https://github.com/WesleyBert/FilmeFlix.git

Navegue até o diretório do projeto:
bash
Copiar código
cd nome-do-repositorio
Instale as dependências do projeto:
bash
Copiar código
npm install
ou
bash
Copiar código
yarn install
Configuração da API do TMDB
Crie uma conta no TMDB.
Obtenha sua chave de API na seção de configurações da conta.
Crie um arquivo .env na raiz do projeto e adicione sua chave de API:
makefile
Copiar código
VITE_TMDB_API_KEY=your_api_key_here
Executando o Projeto
Inicie o servidor de desenvolvimento:
bash
Copiar código
npm run dev
ou
bash
Copiar código
yarn dev
Abra o navegador e acesse http://localhost:3000 para ver a aplicação em execução.

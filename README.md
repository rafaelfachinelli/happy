<div align="center">

<img alt="Happy Ferraz" src=".github/banner.png">

</div>

<p align="center"> 
  <img alt="Tamanho do Repositório" src="https://img.shields.io/github/repo-size/rafaelfachinelli/happy?style=for-the-badge&color=15D6D6">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rafaelfachinelli/happy?style=for-the-badge&color=15D6D6">
  <a href="https://github.com/rafaelfachinelli">
    <img alt="Feito por Rafael Fachinelli" src="https://img.shields.io/badge/feito%20por-Rafael Fachinelli-%15B6D6?style=for-the-badge&color=15D6D6">
  </a>
  <img alt="Licença" src="https://img.shields.io/github/license/rafaelfachinelli/happy?style=for-the-badge&color=15D6D6"/>
<p>

<p align="center">
 <a href="#computer-sobre">Sobre</a> •
 <a href="#memo-roteiro">Roteiro</a> •
 <a href="#triangular_ruler-status-do-projeto">Status</a> •
 <a href="#movie_camera-demonstração">Demonstração</a> •
 <a href="#dvd-executar-o-projeto">Executar</a> •
 <a href="#hammer-tecnologias">Tecnologias</a> •
 <a href="#boy-autor">Autor</a> •
 <a href="#page_facing_up-licença">Licença</a>
</p>

---
## :computer: Sobre

Plataforma web, servidor e aplicativo mobile para cadastro e busca de orfanatos no mapa da região de Ferraz de Vasconcelos, São Paulo - Brasil.

Projeto desenvolvido durante a **Next Level Week#3 (NLW)** na avançada **Trilha Omnistack** oferecida pela [Rocketseat](https://www.rocketseat.com.br).
O NLW é uma experiência online com muito conteúdo prático e desafios com duração de uma semana para conclusão.

---
## :memo: **Roteiro**

<div align="center">
<details>
<summary>Clique para Visualizar</summary>
	
<details>
<summary>WEB Responsivo</summary>

|      Estado      |     Tarefa    |
|      :---:       |      :---     |
|:heavy_check_mark:|Criar estrutura do projeto web com React|
|:heavy_check_mark:|Estruturar página inicial|
|:heavy_check_mark:|Estilizar página inicial|
|:heavy_check_mark:|Estruturar página de busca no mapa|
|:heavy_check_mark:|Estilizar página de busca no mapa|
|:heavy_check_mark:|Criar rotas no React|
|:heavy_check_mark:|Finalizar página de busca no mapa|
|:heavy_check_mark:|Criar navegação entre páginas|
|:heavy_check_mark:|Abstrair componentes|
|:heavy_check_mark:|Conectar plataforma web com servidor|
|:heavy_check_mark:|Listar orfanatos no mapa|
|:heavy_check_mark:|Apresentação dos detalhes do orfanato|
|:heavy_check_mark:|Criação de orfanato|

</details>

<details>
<summary>Servidor</summary>

|      Estado      |     Tarefa    |
|      :---:       |      :---     |
|:heavy_check_mark:|Criar estrutura do servidor com Node.js|
|:heavy_check_mark:|Organizando rotas e parâmetros|
|:heavy_check_mark:|Criando tabelas no banco de dados|
|:heavy_check_mark:|Cadastro de orfanatos implementado|
|:heavy_check_mark:|Configurando controller|
|:heavy_check_mark:|Listagem de orfanatos|
|:heavy_check_mark:|Upload de imagens|
|:heavy_check_mark:|Desenvolvendo views|
|:heavy_check_mark:|Tratamento de excessões|
|:heavy_check_mark:|Validação de dados|

</details>

<details>
<summary>Aplicativo</summary>
	
|      Estado      |     Tarefa    |
|      :---:       |      :---     |
|:heavy_check_mark:|Criar estrutura do aplicativo com Expo|
|:heavy_check_mark:|Organizar projeto|
|:heavy_check_mark:|Criar rotas|
|:heavy_check_mark:|Criar componentes|
|:heavy_check_mark:|Criar páginas e estilos|
|:heavy_check_mark:|Navegação de páginas|
|:heavy_check_mark:|Integração com maps|
|:heavy_check_mark:|Integração com o servidor Node|

</details>
</details>
</div>

---
## :triangular_ruler: **Status do Projeto**

<h4 align="center"> 
	👶 Finalizado.
</h4>

---
## :movie_camera: **Demonstração**

<p align="center"><b> :computer: PLATAFORMA WEB </b></p>

<p align="center">
  <kbd>
    <img style="border-radius: 5px" width="450px" height="250px" alt="Demonstração do Aplicativo Happy Ferraz" src="./.github/demo-desk-map.gif">
  </kbd> 
</p>

<p align="center"><b> :iphone: APLICATIVO </b></p>

<p align="center">
  <kbd>
    <img style="border-radius: 5px" width="150px" height="250px" alt="Demonstração do Aplicativo Happy Ferraz" src="./.github/demo-mobile-happy.gif">
  </kbd> 
</p>

<div align="center">

</div>

---
## :dvd: **Executar o Projeto**

### :desktop_computer: **WEB Responsivo**

Entre na pasta [`web/`](web/) e execute os seguintes comandos:

<details>
<summary><i>com <b>npm</b></i></summary>

```bash
# Instalar dependências
$ npm install

# Iniciar servidor de desenvolvimento
$ npm start
```

</details>

<details>
<summary><i>com <b>yarn</b></i></summary>

```bash
# Instalar dependências
$ yarn

# Iniciar servidor de desenvolvimento
$ yarn start

```

</details>

> ⚠️ O servidor de desenvolvimento iniciará na porta:3000 - Acesse <http://localhost:3000>

### :globe_with_meridians: **Servidor**

Entre na pasta [`server/`](server/) e execute os seguintes comandos:

<details>
<summary><i>com <b>npm</b></i></summary>

```bash
# Instalar dependências
$ npm install

# Criar banco de dados
$ npm typeorm migration:run

# Iniciar servidor
$ npm dev
```

</details>

<details>
<summary><i>com <b>yarn</b></i></summary>

```bash
# Instalar dependências
$ yarn

# Criar banco de dados
$ yarn typeorm migration:run

# Iniciar servidor de desenvolvimento
$ yarn dev
```

</details>

> ⚠️ O servidor iniciará na porta:3333 - Acesse <http://localhost:3333>

> ⚠️ O Banco de Dados fica salvo em [`server/src/database/database.sqlite`](server/src/database/database.sqlite)

### :iphone: **Aplicativo**

Entre na pasta [`mobile/`](mobile/) e execute os seguintes comandos:

<details>
<summary><i>com <b>npm</b></i></summary>

```bash
# Instalar dependências
$ npm install

# Iniciar servidor de desenvolvimento
$ npm start
```

</details>

<details>
<summary><i>com <b>yarn</b></i></summary>

```bash
# Instalar dependências
$ yarn

# Iniciar servidor de desenvolvimento
$ yarn start

```

</details>

> ⚠️ O expo para desenvolvimento iniciará na porta:19002 - Acesse <http://localhost:19002>

> ⚠️ No arquivo **api.ts** dentro da pasta [`mobile/src/services/`](mobile/src/services/) é necessário colocar o seu IP local na variável baseURL, mantendo a porta 3333 do servidor.

---
## :hammer: **Tecnologias**

As seguintes ferramentas foram utilizadas na construção do projeto:

<div align="center">

|WEB Responsivo|Servidor|Aplicativo|
|:---:|:---:|:---:|
|[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5)|[Node.js]()|[React Native](https://reactnative.dev)|
|[CSS3](https://developer.mozilla.org/pt-BR/docs/Archive/CSS3)|[Express]()|[React Navigation](https://reactnavigation.org)|
|[Typescript](https://www.typescriptlang.org)	|[SQLite3]()|[Expo](https://expo.io)|
|[ReactJS](https://pt-br.reactjs.org)|[Yup](https://github.com/jquense/yup)|[Axios](https://github.com/axios/axios)|
|[React Router DOM](https://reactrouter.com/web/guides/quick-start)|[TypeORM](https://typeorm.io)||
|[React Icons](https://react-icons.github.io/react-icons/)|||
|[Leaflet](https://leafletjs.com)|||
|[React Leaflet](https://react-leaflet.js.org)|||
|[Axios](https://github.com/axios/axios)|||

</div>

---
## :boy: **Autor**

<div align="center">

<a href="https://github.com/rafaelfachinelli">
 <img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/19878139?s=460&u=278a6f44f49af3c8edb13a811f7654dfe6e89341&v=4" width="100px;" alt="Foto de Perfil Rafael Fachinelli"/>
 <br />
 <sub><b>Rafael Fachinelli</b></sub></a>


Feito com ❤️ por Rafael Fachinelli 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Rafael_Fachinelli-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaelfachinelli/)](https://www.linkedin.com/in/rafaelfachinelli/)
[![Github Badge](https://img.shields.io/badge/-rafaelfachinelli-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/rafaelfachinelli)](https://github.com/rafaelfachinelli)
[![Itch.io Badge](https://img.shields.io/badge/-rafaelfachinelli-FA5C5C?style=flat-square&logo=itch.io&logoColor=white&link=https://rafael-fachinelli.itch.io/)](https://rafael-fachinelli.itch.io/)
[![Outlook Badge](https://img.shields.io/badge/-rafael.fachinelli@fatec.sp.gov.br-0078d4?style=flat-square&logo=microsoft-outlook&logoColor=white&link=mailto:rafael.fachinelli@fatec.sp.gov.br)](mailto:rafael.fachinelli@fatec.sp.gov.br)

</div>

---
## :page_facing_up: **Licença**

<div align="center">
  
[![License](https://github.com/rafaelfachinelli/rafaelfachinelli/blob/master/.github/license.svg)](./LICENSE)

</div>

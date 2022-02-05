<p align="center">
     <img src="images/Capa.png" alt="Logo" >

  <h5 align="center">Vrum Empress.</h5>

  <p align="center">
    Projeto desenvolido por Matheus Teodoro
    <br />
    <a href="/">Versão web (em breve)</a>
    ·
 
  </p>
</p>

# 🎵 Sobre o projeto

O **Vrum** foi desenvolvido com a proposta de uma aplicação web em React e mobile em React Native que consomem o mesmo back-end em Node.js.

Hoje o Vrum tem a seguinte proposta:
* **Moods** já previamente cadastrados no banco
* Cadastro de **profile** pela aplicação web
* Esse cadastro já integrado com mapa para captura da geolocalização
* Integração com a API do IBGE para requisição de UFs e Cidades
* Pesquisa de **profiles** pelo app mobile
* Um único back-end que gerencia as requisições dos dois apps

### Stack
- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)

### Layouts


# 🖥️ Para usar

### Requisitos

- **[Node.js](https://nodejs.org/en/)** instalado na máquina e de um gerenciador de dependencias (**[npm](https://www.npmjs.com/)** ou **[yarn](https://yarnpkg.com/)**)
- **[Expo](https://expo.io/)** instalado **globalmente**


```sh

```

```sh
  # Instalando as dependências
  $ npm install

  ## Criando o banco (scripts no package.json)
  $ cd server
  $ npm run knex:migrate
  $ npm run knex:seed

  # Rodando o back-end
  $ npm run dev

  # Rodando o app web
  $ cd ../web
  $ npm start

  # Rodando o app mobile
  $ cd ../mobile
  $ npm start
```

---


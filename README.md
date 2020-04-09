<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT Licença][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



[![Product Name Screen Shot][product-screenshot]]()
<!-- PROJECT LOGO -->
<br />
<p align="center">
  

  <h3 align="center">Construindo Primeira API com NodeJS</h3>

  <p align="center">
    Este estudo faz parte do percurso de aperfeiçoamento do Bootcamp da Rocketseat GoStack
    <br />
    <a href="https://github.com/gablemos/first-nodejs-api"><strong>Explore os docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/gablemos/first-nodejs-api">View Demo</a>
    ·
    <a href="https://github.com/gablemos/first-nodejs-api/issues">Report Bug</a>
    ·
    <a href="https://github.com/gablemos/first-nodejs-api/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Tabela de Conteúdo

* [Sobre o Projeto](#sobre-o-projeto)
  * [Construido Com](#construido-com)
* [Começando](#começando)
  * [Pré-requisito](#pré-requisito)
  * [Instalação](#instalação)
* [Uso](#uso)
* [Roadmap](#roadmap)
* [Contribuindo](#contribuindo)
* [Licença](#licença)
* [Contato](#contato)

<p align="center">
<a href="https://github.com/gablemos/first-nodejs-api">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>
</p>

<!-- Sobre o Projeto -->
## Sobre o Projeto


Essa é uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".


### Construido Com

* [NodeJS](https://nodejs.org/en/)
* [ExpressJS](https://expressjs.com/pt-br/)
* [JestJS](https://jestjs.io)
* [Yarn](https://yarnpkg.com)



<!-- Começando -->
## Começando

Para conseguir rodar localmente o projeto siga os passos listados abaixo, são simples.

### Pré-requisito

Tenha pelo menos o Yarn instalado na sua máquina e o Node.


### Instalação
 
1. Clone o repo
```sh
git clone https://github.com/gablemos/first-nodejs-api.git
```
2. Instale osas dependencias
```sh
yarn
```
3. Execute os testes
```sh
yarn test
```
4. Execute o projeto
```sh
yarn dev
```



<!-- USAGE EXAMPLES -->
## Uso

1. Create Repository
```js
POST : {{ base_url }}/repositories
```
```json
{
	"url": "https://github.com/Rocketseat/umbriel",
	"title": "Umbriel",
	"techs": ["Node", "Express", "TypeScript"]
}
```
2. List Repositories
```js
GET : {{ base_url }}/repositories
```
```json
{
	"url": "https://github.com/Rocketseat/umbriel",
	"title": "Umbriel",
	"techs": ["Node", "Express", "TypeScript"]
}
```
3. Update Repository
```js
PUT : {{ base_url }}/repositories/:id
```
```json
{
	"url": "https://github.com/Rocketseat/unform",
	"title": "Unform",
	"techs": ["React", "ReactNative", "TypeScript", "ContextApi"]
}
```
4. Delete Repository
```js
DELETE : {{ base_url }}/repositories/:id
```
5. Add Like to a Repository
```js
POST : {{ base_url }}/repositories/:id/like
```


<!-- ROADMAP -->
## Roadmap

Veja as [issues abertas](https://github.com/gablemos/first-nodejs-api/issues) para futuras features.



<!-- CONTRIBUTING -->
## Contribuindo

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Faça um Fork do projeto
2. Cria sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suasalterações (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request



<!-- LICENSE -->
## Licença

Distribuido sobre a Licença MIT. Veja `LICENSE` para mais informações.



<!-- CONTACT -->
## Contato

Gabriel Lemos - [@greigrao](https://www.instagram.com/greigrao/) - gabrielelias.lemos@gmail.com

Project Link: [https://github.com/gablemos/first-nodejs-api](https://github.com/gablemos/first-nodejs-api)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/gablemos/first-nodejs-api.svg?style=flat-square
[contributors-url]: https://github.com/gablemos/first-nodejs-api/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/gablemos/first-nodejs-api.svg?style=flat-square
[forks-url]: https://github.com/gablemos/first-nodejs-api/network/members
[stars-shield]: https://img.shields.io/github/stars/gablemos/first-nodejs-api.svg?style=flat-square
[stars-url]: https://github.com/gablemos/first-nodejs-api/stargazers
[issues-shield]: https://img.shields.io/github/issues/gablemos/first-nodejs-api.svg?style=flat-square
[issues-url]: https://github.com/gablemos/first-nodejs-api/issues
[license-shield]: https://img.shields.io/github/license/gablemos/first-nodejs-api.svg?style=flat-square
[license-url]: https://github.com/gablemos/first-nodejs-api/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lemosgabriel
[product-screenshot]: images/screenshot.png

# Projeto página de Streaming



| ![Static Badge](https://img.shields.io/badge/Node%20-%20v21.6.1-blue) | ![Static Badge](https://img.shields.io/badge/Json_server%20-%20v0.16.3-blue) | ![Static Badge](https://img.shields.io/badge/Repo%20size%20-%201.68%20MB-blue) | ![Static Badge](https://img.shields.io/badge/License%20-%20Not%20specified-blue) |
|---|---|---|---|

&nbsp;

## ✏️Descrição do Projeto

Este repositório foi criado como parte da imersão da Alura com o propósito de reforçar e explorar na prática alguns conceitos de HTML, CSS e JavaScript. O projeto consiste em uma página no estilo do Spotify, onde os usuários podem explorar artistas. Uma "Fake API" foi desenvolvida e um servidor JSON foi integrado possibilitando o consumo da "Fake API" via JavaScript, assim efetuando a busca desses artistas.

&nbsp;

## 🎬Demonstração

<p align="center">
<img src="src/assets/demonstração.gif">
</p>

&nbsp;
## 💻 Instalação e execução

Clone este repositório, e tenha em sua máquina o [GIt](https://git-scm.com/) e [Node.js](https:/nodejs.org/en/download/current).

&nbsp;

Primeiro instale o Json-server na versão 0.16.3:

```
npm install -g json-server@0.16.3
```

Habilitar no diretório onde foi salvo o arquivo :

```
json-server --watch Seu-diretório\spotify-imersao\api-artists\artists.json --port 3000
```


__Caso o terminal não reconheça o comando anterior:__
```
npx json-server --watch Seu-diretório\spotify-imersao\api-artists\artists.json db.json --port 3000
```

&nbsp;

Vizualizar no navegador a Api após habilitada: 
http://localhost:3000/artists

&nbsp;
## 📖Referências

 - [Spotify Web](https://open.spotify.com/intl-pt)
 - [Artigos Alura](https://www.alura.com.br/artigos)

&nbsp;

## 🚀 Sobre mim

Sou um aspirante a desenvolvedor frontend com forte interesse em HTML, CSS e JavaScript. Determinado a aprender e crescer, estou comprometido em criar experiências digitais cativantes e intuitivas. Pronto para enfrentar desafios e contribuir para projetos inovadores.


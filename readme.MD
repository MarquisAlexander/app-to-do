<h2 align="center">
  🚀 to-do
</h2>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-informações">Informações</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layoutdesktop">Layout Desktop</a>
</p>

## :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ReactNative](https://reactnative.dev/)

## 🤔 Informações

Esse é um pequeno projeto que foi desenvolvido como desafio do curso ignite da rocketseat, nesse app colocamos em prática manipulação de estados e manipulação de objetos.

## 🖼 Layout

<p align="center">
<img src="https://user-images.githubusercontent.com/51330232/120658864-3464f900-c45c-11eb-96e2-cde633b840b2.jpg">
</p>

### :muscle: Quem deu aquela força para não desistir?

Eu estava com dificuldade para rodar o projeto na minha máquina, mas o pessoal do forum me ajudou. [na comunidade da Rocketseat :rocket:](https://discordapp.com/invite/gCRAFhc)

README feito com ❤️ by **Meus amigos e MarquisAlexander**

## Testar Aplicação

Para testar essa aplicação na sua máquina siga os passos abaixo. :)

## Primeiro!!!

- Instale o <a href="https://git-scm.com/">git</a> na sua máquina.

## Download

Primeiro use o `git clone` para fazer o download desse repositório, você pode usar o link abaixo.
https://github.com/MarquisAlexander/to-do.git .
comando completo: `git clone` + link do repositório

## Instalação

- Depois de baixar o projeto
- Abra o seu terminal.
- Navegue até a pasta do projeto que você baixou.
- instale as dependencias executando `npm install` ou `yarn install`
- Já na pasta do projeto você pode usar o comando `npx react-native run-android` ou `yarn android`
- Agora é só esperar a aplicação rodar. :)

caso você enfrente esse erro:

- `error Failed to install the app. Make sure you have the Android development environment set up: https://reactnative.dev/docs/environment-setup. Error: spawn ./gradlew EACCES at Process.ChildProcess._handle.onexit (internal/child_process.js:269:19) at onErrorNT (internal/child_process.js:467:16) at processTicksAndRejections (internal/process/task_queues.js:82:21) info Run CLI with --verbose flag for more details. error Command failed with exit code 1. info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.`

pra resolver esse problema basta rodar o comando `sudo chmod 755 android/gradlew`

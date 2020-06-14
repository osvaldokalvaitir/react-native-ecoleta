# React Native - Ecoleta

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/react-native-ecoleta/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/react-native-ecoleta.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/react-native-ecoleta.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/react-native-ecoleta.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/react-native-ecoleta.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/react-native-ecoleta.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/react-native-ecoleta.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Aplicação Ecoleta usando React Native, Expo, TypeScript, react-native-maps, react-native-picker-select, react-native-svg, @react-navigation/native, @react-navigation/stack, expo-constants, expo-font, expo-location e expo-mail-composer consumindo os recursos da API do [Node.js - Ecoleta](https://github.com/osvaldokalvaitir/nodejs-ecoleta).

## Índice

- [Capturas de Tela](#capturas-de-tela)

  - [Home](#home)

  - [Pontos de coleta](#pontos-de-coleta)

  - [Detalhe](#detalhe)

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

## Capturas de Tela

### Home

![Home](/.github/assets/home.png)
Esta é a primeira tela, que é a apresentação do projeto, é necessário selecionar uma UF e cidade para entrar.

### Pontos de coleta

![Points](/.github/assets/points.png)
Nesta tela, é necessário selecionar os itens desejados e irá aparecer todos os pontos de coletas deste item que são vindos da API.

### Detalhe

![Detail](/.github/assets/detail.png)
Ao selecionar um ponto de coleta no mapa, aparece esta tela, onde estão todas as informações do estabelecimento, podendo entrar em contato via WhatsApp ou e-mail.

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-cli.md) e siga `Execução de Projeto para Desenvolvimento no React Native no Emulador Android e iOS`.

## Utilizados no Projeto

### Bibliotecas

- [@react-navigation/native](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-navigation-native.md)

- [@react-navigation/stack](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-navigation-stack.md)

- [@expo-google-fonts/roboto](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@expo-google-fonts-roboto.md)

- [@expo-google-fonts/ubuntu](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@expo-google-fonts-ubuntu.md)

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Expo CLI](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-cli.md)

- [expo-constants](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-constants.md)

- [expo-font](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-font.md)

- [expo-location](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-location.md)

- [expo-mail-composer](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/expo-mail-composer.md)

- [React Native Gesture Handler](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-gesture-handler.md)

- [React Native MaskedView](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@react-native-community-masked-view.md)

- [react-native-maps](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-maps.md)

- [react-native-picker-select](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-picker-select.md)

- [react-native-reanimated](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-reanimated.md)

- [react-native-safe-area-context](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-safe-area-context.md)

- [react-native-screens](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-screens.md)

- [react-native-svg](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-native-svg.md)

- [TypeScript](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/typescript.md)

### APIs

- **[Node.js - Ecoleta](https://github.com/osvaldokalvaitir/nodejs-ecoleta)**

  - **Rotas**

    - Pontos de coleta

      - Lista pontos filtrados
      - Lista ponto específico
      - Cria ponto de coleta

    - Itens

      - Lista itens

- **[IBGE API](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api/ibge-api.md)**

  - **Rotas**

    - Lista todos os estados

    - Lista todos os municípios de um estado selecionado
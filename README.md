# ReactJS Snippets

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">ReactJS Snippets</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Tabela de Conteúdo

- [Tabela de Conteúdo](#tabela-de-conteúdo)
- [Sobre o Projeto](#sobre-o-projeto)
- [Começando](#começando)
  - [Instalação](#instalação)
  - [Linguagens Suportadas](#linguagens-suportadas)
  - [Snippets](#snippets)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

---

## Sobre o Projeto

Este projeto disponibiliza um conjunto de **Snippets** para acelerar a criação de componentes e arquivos de configuração em aplicações **ReactJS**.  
Suporta **JavaScript**, **TypeScript**, **Styled Components**, testes com **React Testing Library**, além de alguns padrões comuns da comunidade.

---

## Começando

### Instalação

Para instalar a extensão no VSCode:

1. Abra o **Command Palette** com `Ctrl + Shift + P` (Windows/Linux) ou `Cmd + Shift + P` (macOS).
2. Digite `Install Extensions` e pressione `Enter`.
3. Pesquise por **Samuelndm ReactJS** (ou o nome do pacote caso esteja usando um fork/versão própria).
4. Clique para instalar.

---

### Linguagens Suportadas

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

---

## Snippets

Abaixo segue a lista de **gatilhos** disponíveis. O **⇥** representa a tecla `TAB` para expandir o snippet.

| Gatilho                    | Descrição                                                                                 |
| -------------------------- | ----------------------------------------------------------------------------------------- |
| `rc →`                     | Cria um componente **Stateful**                                                           |
| `rrc →`                    | Cria um componente **Stateful** conectado ao **Redux**                                    |
| `rsc →`                    | Cria um componente **Stateless**                                                          |
| `rrsc →`                   | Cria um componente **Stateless** conectado ao **Redux**                                   |
| `rfc →`                    | Cria um componente **Functional** (JS/TS)                                                 |
| `rft →`                    | Cria um componente **Functional** em **TypeScript**                                       |
| `rafc →`                   | Cria um componente **Arrow Function** em **TypeScript** com styled-components e PropTypes |
| `rafcs →`                  | Cria um componente **Functional** com import de arquivo CSS                               |
| `raffc →`                  | Cria um componente **Arrow Function** usando **nome do arquivo** como nome do componente  |
| `styled →`                 | Cria um arquivo de estilização com **Styled Components**                                  |
| `api →`                    | Cria um arquivo de configuração do **Axios**                                              |
| `mapstatetoprops →`        | Cria o método `mapStateToProps` vazio                                                     |
| `mapdispatchtoprops →`     | Cria o método `mapDispatchToProps` vazio                                                  |
| `create-store-react →`     | Cria a configuração do **Redux** com Ducks e Sagas                                        |
| `root-reducer →`           | Cria o arquivo que combina os reducers                                                    |
| `root-saga →`              | Cria o arquivo centralizador de Sagas                                                     |
| `duck →`                   | Cria um Duck padrão                                                                       |
| `rsduck →`                 | Cria um Duck com **Reduxsauce**                                                           |
| `reactotron-react →`       | Configuração do **Reactotron**                                                            |
| `reactotron-redux-react →` | Configuração do **Reactotron** com Redux + Redux Saga                                     |
| `ctl →`                    | Adiciona `console.tron.log`                                                               |
| `ctw →`                    | Adiciona `console.tron.warn`                                                              |
| `cte →`                    | Adiciona `console.tron.error`                                                             |
| `testc →`                  | Cria arquivo de teste com **React Testing Library** para um componente                    |

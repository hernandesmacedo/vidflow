# VidFlow

O VidFlow é uma plataforma de compartilhamento de vídeos.

![Captura de tela do Vidflow.](./vidflow.png)

## 🔨 Funcionalidades do projeto

Os vídeos são buscados de uma API, possui modo escuro e os botões interativos funcionam.

Durante o curso, o código do projeto foi analisado e refatorado.

O desafio foi encontrar pontos de melhoria para tornar o projeto VidFlow acessível para todas as pessoas usuárias. 

## ✔️ Técnicas e tecnologias utilizadas

- `HTML`
- `CSS`
- `JavaScript`
- `JSON Server`
- `Figma`
- `ARIA Authoring Practices Guide (APG)`
- `NVDA - Leitor de tela`
- `Acessibilidade Web`

## Link do Figma

[Acesse o Figma do Vidflow](https://www.figma.com/file/UbPLETdOLAuQk6G09HUtnZ/VidFlow-%7C-Acessibilidade?node-id=0%3A1&mode=dev).

## 🛠️ Abrir e rodar o projeto

Após baixar ou clonar o projeto deste repositório, você precisa ter o [Node.js](https://nodejs.org/) e o [`json-server`](https://www.npmjs.com/package/json-server) instalados.

Caso não tenha o `json-server` instalado globalmente, execute o seguinte comando:

```bash
npm install -g json-server@0.17.4
```

Com o Node.js e o `json-server` instalados, execute o seguinte comando para disponibilizar a API local de vídeos:

```bash
json-server --watch backend/videos.json
```

Em seguida, abra o `index.html` no navegador e o VidFlow já pode ser visualizado!

----
![Imagem de capa do curso. O título é "3486 - Acessibilidade em HTML, CSS e JavaScript" e o subtítulo é "Avaliando e melhorando um projeto com o NVDA".](./thumb.png)
# Medium-clone

This project is shallow copy of [Kent C. Dodds](https://blog.kentcdodds.com/) blog on [medium.com](https://medium.com/). It replicates Medium's most basic features like post reading and post editing. The editor view uses [medium-editor](https://github.com/yabwe/medium-editor) package, which actually made this project possible.

The project is currently in MVP stage (early prototype). More features are planned, they can be found in [roadmap](docs/roadmap.md).

## Motivation (unformal)

This project is a tribute to the [medium.com](https://medium.com/), the great place to read and write articles. The idea was to create my own Medium(with blackjack and stuff) from scratch and learn what is needed to create one. It is inspired by the [realworld](https://github.com/gothinkster/realworld) project, which actually does the same. I wanted to be closer to the original, so I started my own. It can be seen as lowcost-cosplay of Medium ;-P

## Features

- blog screen with posts
- post view screen
- post edit screen
- responsive web desing
- mobile-first
- code-splitting

## Tech Stack

- React 16, React-Router
- styles: SASS, PostCSS(autoprefixer)
- tools: Webpack 4, Babel, ESLint
- backend: Node 8.x, json-server as backend mock

## License

Design and assets belong to [medium.com](https://medium.com/).  
The app code is MIT licensed and free to use.
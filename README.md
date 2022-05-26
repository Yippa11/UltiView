# UltiView

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

# UltiView
A FIFA Ultimate Team Stat-Tracker and Analysis Tool created by Luke Ypsilantis
## About the App
As a long time FIFA addict and enthusiast I have always loved keeping track of  
the stats I get with cards I use every year in Ultimate Team. As I know many  
can relate I get attached to some of these cards and have a tough time selling  
or discarding them after they no longer have a place in my team. Unfortunately  
EA have only ever tracked goals, assists, and appearances for just the players  
in your club. If you get rid of a card those stats are lost forever and even if  
you use the same player but a different version those stats are not kept track  
of. I have always wanted to have an easy way to view/archive my players stats  
from my Ultimate Team games which is why I developed this application. Capable  
of storing extended game stats such as shots, passes, or tackles, UltiView  
allows players to keep an easily accessible and readable record of their  
players stats over the course of the game cycle and beyond.

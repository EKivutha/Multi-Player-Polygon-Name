## Introduction

With recent cases of online chess multiplayer cheating, we aimed to solve this issue using web3 contracts to make sure none of the players cheat, this leaves a permanent record that cannot be altered. [Reference](https://www.theguardian.com/sport/2020/oct/16/chesss-cheating-crisis-paranoia-has-become-the-culture).
Players can join in and choose a row to fill a color, whoever has the most dots in their favour wins

# UI for Four in a Row contract located here: https://gist.github.com/what-the-func/de9efb1ce61d869a4677372ba8c46efe

## Developing

Once you've installed dependencies with `npm install`, start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Technologies used

React
svelte
vite
QuickNode

## UI of live play

The game requires connection to a polygon account

![Player 1 screen play](assets\Player1.png)
![Player 2 screen](assets\Player2.png)
# dRHGSim (dR Hunger Games Simulator)

![Logo](./public/icons/256.png)

Web extension for simulation of brawls between [devRant](https://devrant.com/) users, inspired by Hunger Games.

## Contributing

[Project](https://github.com/orgs/1drcs/projects/1)

[Boilerplate docs](https://github.com/samrum/vite-plugin-web-extension)

## Project Setup

```sh
npm install
```

## Commands

### Build

#### Development, Watch

Rebuilds extension on file changes. Requires a reload of the extension (and page reload if using content scripts)
```sh
npm run watch
```

#### Production

Minifies and optimizes extension build
```sh
npm run build
```

### Load extension in browser

Loads the contents of the dist directory into the specified browser

```sh
npm run serve:firefox
```

```sh
npm run serve:chrome
```

To specify the path to another Chromium-based browser (like Brave):

 1. Create `.env.local` file.

 2. Append this line to the file:
    
    ```properties
    WEB_EXT_CHROMIUM_BINARY=/usr/bin/brave
    ```

![](https://i.imgur.com/B3GoQ4p.png)

<p align="center"><b>MineJS</b> is a javascript-based voxel engine that runs in your browser!</p>

### Disclaimer

:pushpin: This project is a work in progress. There are a lot of potential features waiting to be added!

# Motivation

We thought it would be interesting to design a game that is inspired by the popular voxel engine ["Minetest"](https://www.minetest.net/) with javascript. We are interested to see if javascript can deliver quality graphics and performance, and interactive multiplayer game play within a 3D voxel type environment.

# Screenshots

These are some screenshots taken directly from the project.

## User Authentication

![](https://i.imgur.com/RNzVsKz.png)

![](https://i.imgur.com/He0UBHz.png)

![](https://i.imgur.com/Ra2KnTT.png)

![](https://i.imgur.com/MJEEtFI.png)

## Neatly Styled Game UI

![](https://i.imgur.com/fIVxDQH.png)

![](https://i.imgur.com/A951uaC.png)

## Awesome Graphics

![](https://i.imgur.com/Xpi24GY.png)

![](https://i.imgur.com/FAuiYJe.jpg)

![](https://i.imgur.com/fYrQsAT.png)

![](https://i.imgur.com/B4tDJjw.png)

# Build Stack

Javascript.

## Frontend

- [three.js](https://threejs.org)
- [react.js](https://reactjs.org/)
- [react-router](https://github.com/ReactTraining/react-router)
- [apollo](https://www.apollographql.com/)

## Backend

- [prisma](https://www.prisma.io/docs/1.34/get-started/01-setting-up-prisma-new-database-TYPESCRIPT-t002/)
- [graphql-yoga](https://github.com/prisma/graphql-yoga)

## Authentication

- [bcryptjs](https://github.com/dcodeIO/bcrypt.js/)
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken#readme)

# Features

- Player registration
- Save worlds
- Database support

# Installation

Before cloning the repo or doing anything, be sure to install [docker](https://www.docker.com/) and [node](https://nodejs.org/en/) on your computer. After that, run the following commands:

```bash
# Clone the repository
git clone https://github.com/rdp-studio/mine.js.git

# Download packages for both server and client
yarn
# Start all services
yarn run init # only needed when running for the first time
yarn run start
```

After these commands, visit `localhost:3000`

# Note

:pushpin: mine.js runs fastest on either Opera, Brave or Chrome.

# Sources

- [Voxel Texture](https://opengameart.org/content/voxel-pack)
- [Multiplayer Player Mesh](https://github.com/bs-community/skinview3d)

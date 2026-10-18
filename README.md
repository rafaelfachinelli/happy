<p align="center">
  <img alt="Happy" src=".github/banner.svg" width="400px"/>
</p>

<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rafaelfachinelli/happy?color=3498db&style=for-the-badge">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/rafaelfachinelli/happy?color=3498db&style=for-the-badge">
  <a href="https://rafaelfachinelli.com">
    <img alt="Developed by Rafael Fachinelli" src="https://img.shields.io/badge/Developer-Rafael_Fachinelli-3498db?style=for-the-badge">
  </a>
  <img alt="License" src="https://img.shields.io/badge/License-MIT-3498db?style=for-the-badge">
</p>

<p align="center">
  <a href="#eye_speech_bubble-preview">Preview</a> •
  <a href="#information_source-about">About</a> •
  <a href="#memo-tasks">Tasks</a> •
  <a href="#arrow_forward-run">Run</a> •
  <a href="#hammer_and_wrench-technologies">Technologies</a> •
  <a href="#boy-author">Author</a> •
  <a href="#balance_scale-license">License</a>
</p>

---

## :eye_speech_bubble: Preview

<div align="center">

|Desktop|Mobile|
|:---:|:---:|
|<kbd><img src=".github/demo-desk-map.gif" alt="Happy web"/></kbd>|<kbd><img src=".github/demo-mobile-happy.gif" alt="Happy app" width="260px"/></kbd>|

</div>

---

## :information_source: About

👶 Web platform, server and mobile app to register and find orphanages on the map of the Ferraz de Vasconcelos region, São Paulo, so people can visit them and brighten the children's day. Each orphanage has its location, photos, instructions and opening hours.

Built in 2020 during Rocketseat's Next Level Week #3 (Omnistack track), a one-week online event with practical challenges.

---

## :memo: Tasks

<div align="center">
<details>
<summary>Click to view</summary>

<details>
<summary>🌐 Web</summary>

|State|Task|
|:---:|:---|
|:heavy_check_mark:|Project structure with React|
|:heavy_check_mark:|Landing page|
|:heavy_check_mark:|Orphanages map with Leaflet|
|:heavy_check_mark:|Routes and navigation|
|:heavy_check_mark:|Reusable components|
|:heavy_check_mark:|Integration with the server|
|:heavy_check_mark:|Orphanage details|
|:heavy_check_mark:|Create an orphanage|

</details>

<details>
<summary>🗄️ Server</summary>

|State|Task|
|:---:|:---|
|:heavy_check_mark:|Node.js server structure|
|:heavy_check_mark:|Routes and parameters|
|:heavy_check_mark:|Database tables with TypeORM migrations|
|:heavy_check_mark:|Create and list orphanages|
|:heavy_check_mark:|Image upload with Multer|
|:heavy_check_mark:|Views (response formatting)|
|:heavy_check_mark:|Error handling|
|:heavy_check_mark:|Data validation with Yup|

</details>

<details>
<summary>📱 Mobile</summary>

|State|Task|
|:---:|:---|
|:heavy_check_mark:|Project structure with Expo|
|:heavy_check_mark:|Routes and navigation|
|:heavy_check_mark:|Components, pages and styles|
|:heavy_check_mark:|Map with react-native-maps|
|:heavy_check_mark:|Create an orphanage with photos|

</details>

</details>
</div>

---

## :arrow_forward: Run

You need [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/). For the app, install [Expo Go](https://expo.dev/go) on your phone.

### Server

In the [`server/`](server/) folder:

```bash
# Install dependencies
yarn

# Create the SQLite database
yarn typeorm migration:run

# Start the server
yarn dev
```

> The server starts at <http://localhost:3333>.

### Web

In the [`web/`](web/) folder:

```bash
yarn
yarn start
```

> The app opens at <http://localhost:3000>.

### Mobile

In the [`mobile/`](mobile/) folder:

```bash
yarn
yarn start
```

> Scan the QR code with Expo Go.

---

## :hammer_and_wrench: Technologies

<div align="center">

|Web|Server|Mobile|
|:---:|:---:|:---:|
|[React](https://react.dev/)|[Node.js](https://nodejs.org/)|[React Native](https://reactnative.dev/)|
|[TypeScript](https://www.typescriptlang.org/)|[Express](https://expressjs.com/)|[Expo](https://expo.dev/)|
|[React Router](https://reactrouter.com/)|[TypeORM](https://typeorm.io/)|[React Navigation](https://reactnavigation.org/)|
|[Leaflet](https://leafletjs.com/)|[SQLite](https://www.sqlite.org/)|[React Native Maps](https://github.com/react-native-maps/react-native-maps)|
|[Axios](https://axios-http.com/)|[Multer](https://github.com/expressjs/multer)||
||[Yup](https://github.com/jquense/yup)||

</div>

---

## :boy: Author

<div align="center">

<a href="https://rafaelfachinelli.com">
  <img src="https://github.com/rafaelfachinelli.png" width="100px" alt="Rafael Fachinelli"/>
  <br/>
  <sub><b>Rafael Fachinelli</b></sub>
</a>

Tech Lead and software engineer. Get in touch!

[![Portfolio](https://img.shields.io/badge/-rafaelfachinelli.com-3498db?style=flat-square&logo=googlechrome&logoColor=white)](https://rafaelfachinelli.com)
[![LinkedIn](https://img.shields.io/badge/-Rafael_Fachinelli-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafaelfachinelli/)
[![GitHub](https://img.shields.io/badge/-rafaelfachinelli-000?style=flat-square&logo=github&logoColor=white)](https://github.com/rafaelfachinelli)
[![E-mail](https://img.shields.io/badge/-rafael.l.a.fachinelli@gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rafael.l.a.fachinelli@gmail.com)

</div>

---

## :balance_scale: License

This project is under the [MIT license](./LICENSE).

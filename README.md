<!-- VARS -->

[license-badge]: https://img.shields.io/github/license/joaomnabais/happy
[star-badge]: https://img.shields.io/github/stars/joaomnabais/happy?logo=github
[last-commit-badge]: https://img.shields.io/github/last-commit/joaomnabais/happy
[codacy-badge]: https://app.codacy.com/project/badge/Grade/b2d32fa731984f3e9c3eaa814861c9db
[license-url]: https://github.com/joaomnabais/happy/blob/master/LICENSE
[issues-url]: https://github.com/joaomnabais/happy/issues/
[node-url]: https://nodejs.org/en
[yarn-url]: https://classic.yarnpkg.com/
[npm-url]:  https://www.npmjs.com/
[expo-url]: https://expo.io/

<!-- VARS -->

<p align="center">
  Online platform for visits to orphanages made with Node, React and React Native using Typescript🚀
</p>



<div align="center">  

[![License][license-badge]][license-url]
![Git Stars][star-badge]
![Last Commit][last-commit-badge]
![Codacy Quality][codacy-badge]


</div>


### Content
* [Getting Started](#Getting-Started-)
    * [Cloning](#Cloning)
    * [Requirements](#Requirements)
        * [Backend](#Backend)
        * [Web](#Web)
        * [Mobile](#Mobile)
    * [Running](#Running)
* [Issues](#Issues-)
    * [Report](#Report)
* [License](#License-)

### Getting Started 🚀

#### Cloning

```ps
# Create a directory in your desired location
# Clone the repository inside the directory using git
$ git clone https://github.com/joaomnabais/happy.git
```

#### Requirements
* [Node.js][node-url]
* [Yarn][yarn-url] or [npm][npm-url]
* [Expo][expo-url]

##### Backend 

This project use third party dependencies that need to be installed, use that command to install all needed dependencies

```ps
$ cd backend
$ yarn install
```

>The above command will install all third party dependencies used.
To start the backend you need the database, to make migrations use the command:

```
$ yarn typeorm migration:run
```

##### Web

This project use third party dependencies that need to be installed, use that command to install all needed dependencies
You need to create an account at mapbox.com, copy your default public token and paste into the .env file replacing "YOUR_MAPBOX_TOKEN_HERE" 

```ps
$ cd web
$ yarn install
```

>The above command will install all third party dependencies used.

##### Mobile

This projects use third party dependecies and fonts that need to be installed in development, use that command to install all needed dependencies and fonts

```ps
$ cd mobile
$ yarn install
```
>The above command will install all third party dependencies used.
#### Running

To start the Backend Server run the command

```ps
# Entering in backend directory
$ cd backend
# Run the Backend Server
$ yarn dev
```

To start the Web Server run the command

```ps
# Entering in web directory
$ cd web
# Run the Web Server
$ yarn start
```

To run the Mobile Version run the command

```ps
# Entering in mobile directory
$ cd mobile
# Run the Mobile Version
$ yarn start
```

### Issues 🐛

#### Report

In case you are having any problem you can report in [Issues][issues-url] session.

### License 📝
This project is under the MIT license. See the [LICENSE][license-url] for more information.

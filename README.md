![Logo do Markdown](imagesGit/img1.png)

##### <center> Git Explore </center>
<hr>

# Sobre o Projeto

Este projeto adiciona repositórios do github a uma lista personalizada sua, onde é possível visualizar stars, Forks, Issues.

![Logo do Markdown](imagesGit/tela.png)

# Estrutura de Arquivos
### A estrutura de arquivos está da seguinte maneira:

git-explore
├── src/
│   ├── styles/
│   │   └── global.ts
│   ├── assets/
│   │   ├── githubBackground.svg
│   │   └── logo.svg
│   ├── pages/
│   │   ├── Dashbord/
│   │   │   ├── index.tsx
│   │   │   └── styles.ts
│   │   └── Repository/
│   │       ├── index.tsx
│   │       └── styles.ts
│   ├── services/
│   │   └── api.js
│   ├── store/
│   │   ├── ducks/
│   │   │   └── index.js
│   │   ├── sagas/
│   │   │   └── index.js
│   │   └── index.js
│   ├── index.js
│   └── routes/
│       └──index.tsx
├── .editorconfig
├── .eslintrc.json
├── .gitignore
├── package.json
└── README.md

# Contribuição

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será muito apreciada.

  1. Faça um Fork do projeto
  2. Crie uma Branch para sua Feature (git checkout -b . feature/FeatureIncrivel)
  3. Adicione suas mudanças (git add .)
  4. Comite suas mudanças (git commit -m 'Adicionando 6.uma Feature incrível!)
  5. Faça o Push da Branch (git push origin feature/FeatureIncrivel)
  6. Abra um Pull Request

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

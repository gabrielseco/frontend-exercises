## Git && NPM && Create React App

Este ejercicio es para familiarizarnos con Git, NPM y create-react-app.


### Pasos a seguir

1.- Forkear este repo. En la esquina derecha derecha superior hay un botón que te clonará este repositorio en tu cuenta.

2.- Una vez que esté forkeado copia el enlace de tu repo y en la terminal escribes

```sh
  git clone <url-de-tu-repo>
```

Normalmente este comando se encuentra en la página del repo.

3.- Crear una estructura de React con create-react-app.

4.- Puedes instalar el **cli** de create-react-app con

```sh
  npm i -g create-react-app
  create-react-app frontend-exercise
```

o

```sh
  npx create-react-app frontend-exercise
```

Puedes investigar las diferencias entre estas 2 formas buscando en google. Si buscas en inglés encontrarás más fácil la respuesta.

Una vez que se ha creado todo el repo y en la terminal estás dentro de el sino ejecuta este comando

```sh
  cd frontend-exercise
```

Vamos a subir los cambios a git

```sh
  git add .
  git commit -m "Init repo"
  git push
```

Investiga los comandos git add, git commit and git push
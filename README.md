# vue-sandbox

## Build dev docker image
`docker build -f ./dev.dockerfile -t vue-sandbox-image .`

## Run docker image
`docker run -v ${pwd}\src:/src -p 8080:8080 -d --name vue-sandbox vue-sandbox-image`

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

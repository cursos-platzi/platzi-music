# platzi-music

> A Vue.js project

## Build Setup

### install dependencies
``` bash
npm install
```
### serve with hot reload at localhost:8080
``` bash
npm run dev
```

### build for production with minification
``` bash
npm run build

# deploy to now.sh
mkdir now-dist/
cp -r dist now-dist/ && cp index.html now-dist/
now now-dist/

# set an alias to the url given by now.sh
now alias [nowUrl] [yourURL.now.sh]
```
### deploy to now.sh
``` bash
mkdir now-dist/
cp -r dist now-dist/ && cp index.html now-dist/
now now-dist/
```

### set an alias to the url given by now.sh
``` bash
now alias [nowUrl] [yourURL.now.sh]
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

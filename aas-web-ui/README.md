```shell 
IMAGE=aas-oidc:1.2.9
docker builder prune -af
docker build --platform linux/amd64 --no-cache -t docker-twinmap.letsdev.de/${IMAGE} .
docker tag docker-twinmap.letsdev.de/${IMAGE} docker-twinmap.letsdev.de/${IMAGE}
docker push docker-twinmap.letsdev.de/${IMAGE}
```




# default

## Project setup

```
# yarn
yarn

# npm
npm install

# pnpm
pnpm install
```

### Compiles and hot-reloads for development

```
# yarn
yarn dev

# npm
npm run dev

# pnpm
pnpm dev
```

### Compiles and minifies for production

```
# yarn
yarn build

# npm
npm run build

# pnpm
pnpm build
```

### Customize configuration

See [Configuration Reference](https://vitejs.dev/config/).

## setup

```
mkdir  tailwind-webpck-demo && cd tailwind-webpck-demo
```

```
npm init -y
npm install --save-dev webpack webpack-cli webpack-dev-server babel-loader @babel/core @babel/preset-env style-loader css-loader postcss postcss-loader postcss-preset-env
npm install --save-dev tailwindcss@3.0.7
```

```
mkdir dist src && touch dist/index.html src/index.js src/style.css
```

## build

```
npx tailwindcss init
npx run build
```

## test

```
npm start
```

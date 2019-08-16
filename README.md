# flexible-pc-full-screen
> demo for a flexible pc full screen page, which keep aspect ratio for any screen

Based on [postcss-px-to-rem](https://github.com/QuellingBlade/postcss-px-to-rem) and [lib-flexible-for-dashboard](https://github.com/QuellingBlade/lib-flexible-for-dashboard)

introduce：https://www.njleonzhang.com/2018/08/15/flexible-pc-full-screen.html

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

### IE兼容性问题
```
node_modules\lib-flexible-for-dashboard\dist\index.js
修改 e = 16/9 修改为 e = e ? e : 16 / 9
```

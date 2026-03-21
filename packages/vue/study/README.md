## 安装依赖

```aiignore
$env:PUPPETEER_SKIP_DOWNLOAD="true"; pnpm i
```
- $env:PUPPETEER_SKIP_DOWNLOAD="true"; 为设置环境变量跳过 Puppeteer 的浏览器下载（推荐，因为 Vue 源码分析不需要浏览器测试）

## 打包
```aiignore
pnpm run build
```

## 开启source-map
```aiignore
pnpm run build:source-map
```
或者
```aiignore
pnpm run build --source-map
```
或者
package.json里面加参数(测试使用该方法)
```aiignore

 "build": "node scripts/build.js -s",
```



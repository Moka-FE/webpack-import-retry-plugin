## 使用方法

```javascript
import RetryPlugin from '@moka-fe/webpack-import-retry-plugin'

// with webpack-chain
chainWebpack(config) {
  config.plugin('retry').use(ImportRetry);
```

// 同时在 window 上挂载两个变量
  window.PUCLIC_PATH = 'xxx'  // 当前的 publicPath
  window.CDN_FALLBACK_ORIGIN = ''  // fallback 时要替换成的路径
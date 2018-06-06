# 序

## React Native

- Facebook 公司推出用來建構移動應用的 JavaScript 框架
- Facebook 早先開源的介面渲染框架 React 在原生移動應用平台的延伸產物
- 支持 iOS 和 Android 兩大平台
- Learn once, write anywhere
- Github 52000 star
- 學習成本低

## 技術實現

- 拋棄傳統瀏覽器加載思路 (H5)，轉採用曲線調用原生 API 的思路來渲染介面，獲得媲美原生應用的體驗
- 具體實現思路：

  1. 應用啟動後會從 Server 下載最新的 JSBundle 文件
  2. 透過本地的 JavaScriptCore 引擎對 JS 文件進行解析
  3. 利用 Bridge 映射到對應的原生 API 上，進而調用原生方法和 UI 組件來渲染介面

- 採用 JSX 替代常規的 JavaScript
- 模組化結構，簡單化應用版本的更新迭代

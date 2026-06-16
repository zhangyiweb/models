# models

Three.js 模型资源仓库。

## 资源直链用法

GitHub 页面上的文件链接（`blob` 格式）不能直接作为图片、模型等资源的加载地址，需要转换为 `raw.githubusercontent.com` 直链。

### 转换规则

将链接中的：

```
https://github.com/{用户名}/{仓库名}/blob/{分支}/{文件路径}
```

替换为：

```
https://raw.githubusercontent.com/{用户名}/{仓库名}/{分支}/{文件路径}
```

即：**去掉 `github.com` 中的 `/blob`，并把域名改为 `raw.githubusercontent.com`**。

### 示例

封面图：

| 类型 | 链接 |
| --- | --- |
| GitHub 页面链接（不可直接加载） | `https://github.com/zhangyiweb/models/blob/main/cover/微信图片_20250530093132.png` |
| 直链（可用于代码中加载） | `https://raw.githubusercontent.com/zhangyiweb/models/main/cover/微信图片_20250530093132.png` |

在 Three.js 或其他项目中，请使用 **直链** 地址：

```js
const coverUrl = 'https://raw.githubusercontent.com/zhangyiweb/models/main/cover/微信图片_20250530093132.png';
```

# 交接文档

## 关于仓库

仓库本质上就是 fork 了 html-loader 的 0.5.5 版本

在该仓库，我只加了以下代码：

```javascript
// 新增逻辑：用于处理内容区域
if (typeof config.disposeContent === 'function') content = config.disposeContent(content);
```

该代码用途：
  将页面 html 中原本为云客橙 `#f65c2d` 的颜色，替换为 `css variable` 的方式。

  具体查阅 `p_yunke_back` 搜索关键词 `disposeContent` 即可
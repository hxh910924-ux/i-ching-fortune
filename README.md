# 周易六爻 · 运势预测

一个古风风格的周易六爻（纳甲筮法）运势预测网页应用，支持起卦、卦象收藏与卦象对比，纯前端实现，可离线安装（PWA）。

## 本地运行

直接用任意静态服务器打开项目根目录即可，例如：

```powershell
cd i-ching-fortune
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 目录结构

```text
i-ching-fortune/
├── index.html      # 主页面（样式与逻辑均为内联）
├── manifest.json   # PWA 清单
└── sw.js           # Service Worker
```

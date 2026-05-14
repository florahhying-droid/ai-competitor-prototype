# Product Prototypes

这个仓库用于集中管理产品需求的交互原型。发布到 GitHub Pages 后，根目录 `index.html` 是所有原型的目录页。

## 当前原型

- `competitor-ai/`：AI 推荐竞品链接功能
- `accessory-log/`：配件产品尺寸重量日志

## 新增一个需求原型

1. 在根目录新建一个需求文件夹，例如 `new-feature/`。
2. 把这个需求的页面放到 `new-feature/index.html`。
3. 如果有图片等资源，放到 `new-feature/assets/`。
4. 在根目录 `index.html` 里新增一张卡片，链接到 `./new-feature/`。

推荐保持这种结构：

```text
product-prototypes/
├── index.html
├── competitor-ai/
│   └── index.html
├── accessory-log/
│   ├── index.html
│   └── assets/
└── README.md
```

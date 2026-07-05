# AIVORA Enterprise Website

AIVORA 企业官网静态页面原型，围绕 AI 产品与企业级 IT 服务打造，包含首页、服务中心、业界动态、关于我们等栏目。

## 项目亮点

- 科技蓝视觉风格，结合玻璃质感、发光产品矩阵与企业级深色界面。
- 首页集中展示 FIM、风水、数字人等产品方向。
- 服务中心覆盖 AI 驱动的云端部署、软件开发、自动化测试方案。
- 业界动态与关于我们模块提供完整官网信息结构。
- 纯静态实现，无需构建工具，直接浏览器打开即可预览。

## 文件结构

```text
.
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── hero-products.png
    ├── product-fim.png
    ├── product-feng.png
    ├── product-human.png
    ├── service-cloud.png
    ├── service-code.png
    ├── service-shield.png
    └── ...
```

## 本地预览

直接用浏览器打开 `index.html`。

也可以启动一个简单静态服务器：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## 技术说明

- HTML5 语义结构
- CSS 响应式布局与视觉动效
- 原生 JavaScript 导航交互
- 图片素材位于 `assets/`

## 品牌定位

AIVORA 由资深互联网从业者组成，专注于通过 AI、云端架构、软件工程与自动化测试能力，帮助企业构建可靠、精致、可持续演进的数字产品。

请帮我创建一个基于 Three.js 的网页，要求如下：

1. 使用原生 HTML + JavaScript（不要使用框架，如 React 或 Vue）。
2. 使用 Three.js 最新稳定版本，通过 CDN 引入。
3. 创建一个基础 3D 场景，包括：
 - 场景（Scene）
 - 相机（PerspectiveCamera）
 - 渲染器（WebGLRenderer）
4. 在场景中添加：
 - 一个旋转的立方体（BoxGeometry）
 - 一个光源（如 DirectionalLight 或 AmbientLight）
 -添加阴影效果（开启 renderer.shadowMap）
5. 实现动画循环（requestAnimationFrame），让立方体持续旋转。
6. 支持窗口 resize 自适应。
7. 代码结构清晰，并添加必要注释说明每一步作用。
8. 页面加载后即可直接运行（无需构建工具）。
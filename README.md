# Gesture Particles · 粒子意象

一个由摄像头手势实时控制的 Three.js 3D 粒子艺术系统。

## 在线体验

[打开公开网站](https://gesture-particles-3d.yuguanjian666.chatgpt.site)

## 功能

- 单手张合控制粒子聚拢与扩散
- 单指左右摆动控制粒子旋转
- 单指远近移动控制视觉缩放
- 爱心、花朵、土星、烟花、地球、千里江山和昙花七种粒子形态
- 实时颜色调节、全屏模式和移动端响应式界面
- 鼠标拖动旋转、滚轮缩放的备用控制

## 本地运行

摄像头 API 需要 HTTPS 或 localhost，不能直接通过 file:// 运行。

```bash
python -m http.server 8765
```

然后打开 http://127.0.0.1:8765 。

首次点击“开启手势控制”时，请允许浏览器访问摄像头。

## 技术栈

- Three.js
- MediaPipe Tasks Vision
- WebGL / GLSL
- 原生 HTML、CSS 与 JavaScript

## 隐私

摄像头画面只在浏览器本地用于实时手势识别，不会上传到服务器。

## License

[MIT](LICENSE)

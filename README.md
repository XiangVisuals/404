# 404 Error 页面 README

这个项目是一个定制化的 404 错误页面，带有独特的视觉效果和交互功能，旨在提供一种科技感十足、现代化的用户体验。页面包含了背景噪点、屏幕扫描效果和终端提示等设计元素，同时会自动进行倒计时并跳转至指定的新地址。

## 功能

- **背景效果**：页面背景结合了渐变色与 GIF 动态效果，增加了现代感和科幻感。
- **扫描效果**：通过 CSS 动画实现了屏幕扫描的效果，给用户带来终端风格的体验。
- **终端提示**：通过模拟终端界面显示错误代码和提示信息。
- **自动跳转**：页面加载后会进行 3 秒倒计时，倒计时结束后自动跳转至新的页面。如果没有自动跳转，用户可以点击提供的链接手动跳转。

## 如何使用

1. 克隆该项目或将 `index.html` 文件上传至您的 Web 服务器。
2. 根据需要修改 `redirectUrl` 变量，设置自动跳转的目标地址。
3. 上传后，当访问无效页面时，用户将看到定制化的 404 错误页面。

## 自定义

### 修改背景
背景的噪点和 GIF 动画可以根据您的需求替换：
```css
background-image: url("新的 GIF 地址");

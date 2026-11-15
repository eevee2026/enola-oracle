# ENOLA · 神谕圣物

ENOLA 投资人体验版 H5。以用户提供的产品概念图为视觉基底，体验「拨动星环 → 等待停稳 → 点击中央符文 → 揭示原创神谕卡」。

## 在线体验

部署完成后访问：<https://eevee2026.github.io/enola-oracle/>

## 运行

本项目为单文件、零依赖静态网页。可直接使用任意静态服务器：

```bash
python3 -m http.server 4173
```

然后访问 http://localhost:4173。

## 已实现

- 手机优先的响应式首页与 ENOLA 产品概念图
- Pointer Events 手势拖动星环，带惯性减速
- 星环停稳后才可点击中央骰子
- 六张原创神谕卡：星启、月隐、回响、逆行、转轨、归航
- 卡牌翻转、中文解读、再次占星
- 键盘辅助操作与减少动态效果偏好
- 图片内嵌于 HTML，卡牌图案由 SVG 动态生成；无需额外资源或构建步骤

## GitHub Pages

仓库已包含 `.github/workflows/deploy.yml`。推送到 `main` 后会尝试通过 GitHub Actions 发布 Pages。若首次部署提示 Pages 尚未启用，请在仓库 Settings → Pages 中将 Source 设为 GitHub Actions，再重新运行工作流。

## 重要边界

- 这是基于产品渲染图和独立 SVG 星环的 2.5D 概念 Demo，不是可制造的 3D 机械模拟。
- NFC 与微信小程序尚未接入；页面明确标注为网页模拟交互。
- 六张卡牌属于原创体验文案，不构成真实预测、心理咨询或专业建议。

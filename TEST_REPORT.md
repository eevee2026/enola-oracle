# ENOLA H5 · 部署前检查

## 静态检查
- HTML 使用内嵌 CSS / JavaScript，无第三方运行时依赖。
- 产品图以 WebP data URI 内嵌，卡牌 SVG 由脚本动态生成。
- 页面包含移动端 viewport、safe-area 处理和 reduced-motion 支持。
- 手势采用 Pointer Events，星环设置 touch-action: none。
- 键盘方向键可旋转星环。

## 上线后仍需实测
- GitHub Actions 部署是否成功。
- GitHub Pages HTTPS 公开地址是否可访问。
- iPhone Safari 和 Android Chrome 真机触控、惯性和页面滚动行为。
- 六张卡的完整抽取和再次占星流程。

## 限制
部署前的静态代码检查不能代替真实手机与线上访问验收。当前交互是 2.5D 视觉演示，不代表真实机械 3D 或 NFC 已经联调。

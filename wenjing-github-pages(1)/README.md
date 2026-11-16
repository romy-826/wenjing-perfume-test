# 闻境 · 气味肖像

一款文艺风格的十二香水人格测试。用户完成 16 道题后，会获得主气味人格、隐性人格、推荐香材和避雷方向。

## 在线发布

本仓库已按 GitHub Pages 的静态网站结构整理，`index.html` 位于仓库根目录。

1. 在 GitHub 创建一个新仓库。
2. 将本文件夹内的所有文件上传到仓库根目录。
3. 打开仓库的 `Settings` → `Pages`。
4. 在 `Build and deployment` 下选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，然后点击 `Save`。
6. 等待 GitHub 生成网站地址。

网站地址通常为：

```text
https://你的用户名.github.io/仓库名/
```

## 文件说明

- `index.html`：网站入口
- `style.css`：视觉和移动端样式
- `script.js`：题目、计分与结果逻辑
- `assets/`：产品视觉素材
- `.nojekyll`：让 GitHub Pages 直接发布静态文件

## 数据统计

当前版本尚未接入访问统计。若需要查看开始测试、完成测试和人格结果分布，可以在 `index.html` 中加入 GA4 统计代码，并在 `script.js` 中发送自定义事件。

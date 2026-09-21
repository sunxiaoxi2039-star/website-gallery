# Website Gallery — 网站画廊

我的网站聚合导航站。每个展览两个入口：**GitHub Pages（国际）** 与 **Kimi（中国）**。

## 如何新增一个展览

编辑 `index.html` 顶部的 `EXHIBITIONS` 数组，加一段配置（文件内有注释说明），提交即生效。

## 如何开启 GitHub Pages

仓库 Settings → Pages → Source 选 `Deploy from a branch` → Branch 选 `main / (root)` → Save。
几分钟后访问 `https://sunxiaoxi2039-star.github.io/website-gallery/`。

## 案例 Prompt（2026-09-19）

首页三个新案例默认展开 Prompt，可复制完整文本，移动端支持阅读；点击复制不会打开案例。
- 月面车、Habitat：本次用户原始制作需求。
- 四季小屋：依据已完成的模型、源码与六场景反推的从零制作说明，非博主原始 Prompt；没有做单次重新生成一致性实验。完整文本位于 prompts/moonlit-forge.txt。

检查：三段完整剪贴板内容一致；三处默认可见；展开收起正常；390px 手机无横向溢出；无页面运行错误。
本地入口：http://127.0.0.1:5180/website-gallery/ 。Prompt 已于 2026-09-21 公开上线并通过正式 HTTPS 浏览器验证。

## 线上修复记录 · 2026-09-21

Kimimotion 原 GitHub 子路径返回 404，入口现改为已实测可用的 https://kimimotion.ok.kimi.link/ 。首页现含 SELENE、Habitat、四季小屋及对应三个 Prompt；月面车可从首页进入并持续行驶。发布验证版本：画廊 827b326、子站 7548860，两个 Pages 工作流均成功。正式页面复制、手机布局和运行检查通过。

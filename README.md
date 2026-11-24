# 万圣夜（Halloween）

这是一个浏览器运行的单人回合制恐怖战术卡牌游戏项目。

## 当前版本

- 已将原始 HTML 原型放入仓库根目录 `index.html`。
- 当前可玩角色：迈克尔·迈尔斯（The Shape）。
- 核心玩法：3×3 房间地图、行动力（AP）、战术卡牌、居民恐慌与崩溃、居民 AI、恶念觉醒、警方警戒和关卡结算。
- 鬼面（Ghostface）目前只是预留入口，尚未实现完整玩法。

## 在线发布（GitHub Pages）

1. 打开仓库 **Settings → Pages**。
2. 在 **Build and deployment** 中选择 **Deploy from a branch**。
3. Branch 选择 `main`，目录选择 `/(root)`，然后保存。
4. 等待 GitHub Pages 部署完成。网站地址通常为：
   `https://ren-scarlet.github.io/Halloween/`

## 修改游戏

目前游戏逻辑和界面仍集中在 `index.html`，先以保留原型功能为主。后续会逐步把卡牌、角色、地图配置与核心规则拆分，降低修改卡牌数值和机制的难度；拆分时会保留浏览器直接游玩的部署方式。

## 注意

当前仓库保存的是原型迁移版本，不代表已经完成全面重构或所有机制验收。修改后请通过浏览器实际测试，再视为完成。

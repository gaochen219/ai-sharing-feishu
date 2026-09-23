# AI 落地的核心，是让 AI 更聪明吗？

> 一个客户的视角 — GLP 的 AI 落地经验与踩过的坑
> 飞书 AI Solution Workshop · 2026.09.23 · Chen Gao 高晨

---

## 怎么播放

**GitHub 网页上无法播放** — 它只显示源码不渲染。必须下载到本地。

### 方式一：单文件（推荐上台用）

下载 **`deck-standalone.html`** 一个文件即可，图片已内嵌，换电脑/U 盘/微信传都不会丢图。

浏览器打开 → 按 `F` 全屏。

### 方式二：整个仓库

```bash
git clone https://github.com/gaochen219/ai-sharing-feishu.git
cd ai-sharing-feishu && open index.html   # Windows: start index.html
```

或直接下载 ZIP：`https://github.com/gaochen219/ai-sharing-feishu/archive/refs/heads/main.zip`
（必须解压整个文件夹，`index.html` 依赖 `assets/`）

---

## 操作

| 键 | 作用 |
|---|---|
| `→` / `空格` / `↓` | 下一页 |
| `←` / `↑` | 上一页 |
| `F` | 全屏切换 |
| `Home` / `End` | 首页 / 末页 |
| 点击底部刻度 | 跳到任意页 |
| 左右滑动 | 手机 / 触摸屏翻页 |

---

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | deck 本体（依赖 `assets/`） |
| `deck-standalone.html` | 单文件版，图片内嵌，**上台用这个** |
| `SPEAKER-NOTES.md` | **讲稿要点** — 每页时长、必讲/可跳过、口述备弹、分寸提醒 |
| `assets/` | 产品截图 |

---

## 10 页结构

| # | 页面 | 问题 |
|---|---|---|
| 1 | 封面 | AI 落地的核心，是让 AI 更聪明吗？ |
| 2 | 自我介绍 · π 型 | 如果我是你的客户，你会怎么向我提案？ |
| 3 | Active Sharer | 为什么我愿意把坑都讲出来？ |
| 4 | 全景 | 6 个月，一个团队能做出多少 AI 应用？ |
| 5 | AI-Buddy 3.0 | 从「能跑」到「能上生产」，差的是什么？ |
| 6 | 有趣的 idea | 一个 AI 团队的「下班时间」在干嘛？ |
| 7 | 六类坑 ★ | 最贵的一段路是什么？ |
| 8 | 一条主线 ★★ | 你的场景，真的需要一个会说话的模型吗？ |
| 9 | 外部信息 | 行业这一周发生了什么？ |
| 10 | 引发思考 | 三个讨论题 |

★ 必讲　★★ 全场最高点　时间紧时先砍 P9，再压 P3 / P6

---

## 待办

- [ ] **P3 照片位待补** — 替换 `index.html` 中 P3 的 `.ph` 占位块，然后重新生成单文件版

---

⚠️ 仓库含内部数据，保持 **private**，不要开 GitHub Pages。

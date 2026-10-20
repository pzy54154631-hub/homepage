# Ziyu Peng — 个人学术主页

这是 **Ziyu Peng** 的个人学术主页源代码仓库。目前就读于 **University of Colorado Boulder（科罗拉多大学博尔德分校）**，学习统计与数据科学，此前就读于西交利物浦大学。

[个人主页](https://pzy54154631-hub.github.io/homepage/) · [荣誉与奖项](https://pzy54154631-hub.github.io/homepage/#honors) · [个人简历](https://pzy54154631-hub.github.io/homepage/cv.html) · [English README](README.md)

## 研究与项目

研究兴趣包括统计学习、模型评估和可靠的人工智能系统。主页展示的工作包括：

- 股票收益预测与低换手率选股。
- 面向歧义的视觉问答。
- 用于抽象视觉推理的精度加权对象文件预测编码。
- Corridor Wealth：可审计的 AI 财富顾问原型。

项目介绍及已有代码链接见主页的 [Selected work](https://pzy54154631-hub.github.io/homepage/#work) 部分。

我正在寻找由教师指导的本科科研机会。

## 荣誉与奖项

以下比赛进展截至 2026 年 10 月：

| 项目 | 内容 |
| --- | --- |
| 2026 Shenzhen International FinTech Competition（FinTechathon） | **数据分析赛道：Top 25（前 10%），半决赛进行中。** 另参加 **International AI Track（国际 AI 赛道）**。 |
| CU Boulder Transfer Excellence Scholarship | 2026 年 · 总额 12,000 美元 |
| XJTLU Academic Scholarship | 2026/27 学年 |
| XJTLU Biostatistics Competition 三等奖 | 2026 年 |

Top 25 / 前 10% 对应的是**数据分析赛道**；**国际 AI 赛道**的状态为参赛。相同内容也已写入[主页源代码](index.html)和[简历源代码](cv.html)。

## 源代码与部署

本仓库是 [pzy54154631-hub.github.io/homepage](https://pzy54154631-hub.github.io/homepage/) 的源代码仓库。

- **部署来源：** `main` 分支的 `/ (root)`，GitHub Pages 设置为 **Deploy from a branch**。
- **网页首页：** [`index.html`](index.html)，包含 `#honors` 荣誉部分。
- **当前简历：** [`cv.html`](cv.html)，可通过页面上的 Print / Save as PDF 按钮打印或另存为 PDF。
- **仓库首页说明：** `README.md` 和 `README.zh-CN.md`，用于 GitHub 仓库展示。

网站修改需要提交并推送到 `main`，随后由 GitHub Pages 构建并发布该提交。部署进度可在 [Actions](https://github.com/pzy54154631-hub/homepage/actions) 中查看。核验时应确认成功的 Pages 运行对应目标 commit，再检查线上页面内容。

网站采用静态 HTML，当前样式直接写在 `index.html` 和 `cv.html` 中，无需安装依赖或运行应用构建命令。

## 文件说明

```text
.
├── index.html          # 个人主页、研究项目、教育经历和荣誉
├── cv.html             # 当前可打印简历
├── README.md           # 英文仓库说明
├── README.zh-CN.md      # 中文仓库说明
├── LICENSE.md
└── assets/
    ├── img/            # 头像、网站图标及其他图片
    ├── cv/             # 较早的 PDF 和 TeX 简历文件
    ├── css/            # 保留的模板样式
    └── js/             # 保留的模板脚本
```

更新荣誉信息时，请同步维护 `index.html`、`cv.html` 和两份 README，保持内容一致。

## 来源与许可证

最初基于 Yuheng Yang 的 [Luka Homepage Template](https://github.com/wzsyyh/luka-homepage-template)，现已定制为 Ziyu Peng 的个人学术主页。原有 MIT 许可证和版权声明见 [LICENSE.md](LICENSE.md)。

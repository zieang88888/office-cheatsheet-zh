![banner](assets/banner.svg)

# 中文办公效率速查手册 📊

> **给所有不用写代码的职场人。** Excel 公式、WPS 快捷键、PPT 排版、Word 技巧——把办公室每天都要用、却总记不住的那点东西，一次整理成册。**收藏这一份就够了。**

`office-cheatsheet-zh` 是一份**纯 Markdown 的中文办公速查手册**：打开即用、无需安装、可打印、可搜索。内容按「岗位场景」组织——财务有财务篇，行政有行政篇，运营有运营篇；通用技巧单独成册，谁都能查。

## 为什么值得收藏

- 🎯 **受众最广的开源品类之一**：每个用 Office / WPS 的职场人都是读者，不限程序员。
- 📌 **收藏型手册**：公式、快捷键这类内容，今天用不上、明天一定用得上——**Star 一下，用到的时候找得到**。
- 🪶 **零门槛**：不教 VBA、不教宏、不教编程，只讲"点鼠标和写公式"能解决的事。
- ♻️ **长期有效**：Office 功能十年不变，内容一次整理，十年后依然能用。
- 📋 **按岗直达**：财务、行政/HR、运营三本岗位手册 + 通用公式/快捷键/PPT/Word 四本基础手册 + 三张可直接套用的模板。

## 速查索引（想学什么 → 打开哪篇）

| 我想…… | 打开 |
| --- | --- |
| 写公式：VLOOKUP / SUMIFS / 数据透视… | [Excel 公式速查](cheatsheets/excel-formulas.md) |
| 记住快捷键：Ctrl+; / Alt+= / F2… | [Excel/WPS 快捷键速查](cheatsheets/excel-shortcuts.md) |
| 做 PPT：排版原则 / 放映技巧 | [PPT 制作与演示速查](cheatsheets/ppt-design.md) |
| 用 Word：自动目录 / 邮件合并 / 页码 | [Word 高效操作速查](cheatsheets/word-productivity.md) |
| 我是财务：对账 / 税点 / 账龄 | [财务岗位速查](cheatsheets/finance.md) |
| 我是行政/HR：考勤 / 身份证 / 合同 | [行政/HR 岗位速查](cheatsheets/admin-hr.md) |
| 我是运营：同比环比 / 日报周报 | [运营/市场岗位速查](cheatsheets/operations.md) |
| 周报 / 月报 / 会议纪要直接套 | [模板区](templates/) |

## 快速开始

```bash
git clone https://github.com/zieang88888/office-cheatsheet-zh.git
cd office-cheatsheet-zh
# 然后直接用浏览器 / Typora / VS Code 打开任意 .md 文件
```

或者**什么都不用装**：直接在浏览器里打开 `cheatsheets/excel-formulas.md` 就能看（GitHub 网页端自动渲染 Markdown）。

**打印友好**：在浏览器里打开任意速查文件 → Ctrl+P → 导出为 PDF，就是一张可贴在工位上的 A4 速查表。

## 手册结构

```
office-cheatsheet-zh/
├── cheatsheets/            # 七本速查手册（通用 ×4 + 岗位 ×3）
│   ├── excel-formulas.md   # Excel 公式（查找/统计/文本/日期/技巧）
│   ├── excel-shortcuts.md  # Excel & WPS 快捷键
│   ├── ppt-design.md       # PPT 排版与演示
│   ├── word-productivity.md# Word 高效操作
│   ├── finance.md          # 财务/会计岗位
│   ├── admin-hr.md         # 行政/HR 岗位
│   └── operations.md       # 运营/市场岗位
├── templates/              # 可直接套用的模板
│   ├── weekly-report.md    # 周报
│   ├── monthly-report.md   # 月报
│   └── meeting-notes.md    # 会议纪要
└── assets/                 # 仓库配图（原创 SVG）
```

## 内容示例（摘自 Excel 公式速查）

```markdown
### VLOOKUP 精确查找
- **公式**：`=VLOOKUP(查找值, 表格区域, 要返回第几列, 0)`
- **示例**：`=VLOOKUP(A2, 员工表!$A$2:$D$500, 4, 0)` —— 用工号查姓名
- **注意**：最后的 `0` 表示精确匹配，一定不要省
```

每一条都长这样：**作用 / 公式 / 示例 / 注意**，照着抄就能用。

## 质量承诺

- ✅ 每条速查都经过准确性自查，宁缺毋滥（拿不准的宁可不收）
- ✅ 全部原创中文措辞，不搬运任何教程原文
- ✅ 无占位符、无"待补充"——打开就能用
- ❓ 发现错误？开一个 [Issue](https://github.com/zieang88888/office-cheatsheet-zh/issues)，核实后会第一时间修正

## 星标理由（认真脸）

如果你现在用不上，**也请先 Star**——下次领导让你"快速做个汇总表"，你翻到这里时，就知道这份手册值多少了。⭐

## License

[MIT](LICENSE) © zieang88888

---

*随手整理，长期维护。希望每个加班做表的晚上，这份手册都能让你早点下班。*

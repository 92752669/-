# 文献检索库

铁氧体 / 自旋电子学方向的文献检索、阅读笔记与引用管理。

## 目录结构

```
.
├── README.md          本文件:用法与约定
├── refs.bib           BibTeX 文献库(所有读过/要引用的论文)
├── searches/          检索记录:每次检索一个文件,记下关键词、数据库、结论
│   └── TEMPLATE.md
├── notes/             阅读笔记:每篇重要论文一个文件
│   └── TEMPLATE.md
└── topics/            按主题整理的综述性笔记(如 YIG 薄膜、自旋泵浦、磁振子)
```

## 工作流程

1. **检索**:在 `searches/` 下复制 `TEMPLATE.md`,按日期命名(如 `2026-10-17-yig-spin-pumping.md`),记录检索式和筛选结果。
2. **入库**:值得读的论文,把 BibTeX 条目加进 `refs.bib`,引用键统一用 `第一作者姓小写 + 年份 + 关键词`,如 `kajiwara2010bose`。
3. **精读**:在 `notes/` 下复制 `TEMPLATE.md`,文件名与引用键相同,写下问题、方法、结论、对自己课题的启发。
4. **归纳**:同一主题读了几篇后,在 `topics/` 里写一份横向对比。

## 检索来源(建议)

- Web of Science、Google Scholar、arXiv (cond-mat.mtrl-sci / cond-mat.mes-hall)
- 常用期刊:Phys. Rev. B、Phys. Rev. Lett.、Appl. Phys. Lett.、J. Magn. Magn. Mater.、Nature 系列
- 追引用:从关键论文出发,看它的参考文献(向前)和被引文献(向后)

## 约定

- 笔记用 Markdown,中文为主,专有名词保留英文。
- 每条检索记录写清楚日期和检索式,方便以后复查、补充。

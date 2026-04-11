# 运营数据仓库

集中管理各公司电商平台的运营数据、分析报告与汇总文档，便于随时查阅与复用。

## 目录结构

```
Operations Repository/
├── safesav/
│   ├── alibaba/    data/ reports/ others/
│   ├── aliexpress/ data/ reports/ others/
│   ├── mic/        data/ reports/ others/
│   ├── taobao/     data/ reports/ others/
│   └── 1688/       data/ reports/ others/
└── angrui/
    ├── alibaba/    data/ reports/ others/
    ├── aliexpress/ data/ reports/ others/
    ├── mic/        data/ reports/ others/
    ├── taobao/     data/ reports/ others/
    └── 1688/       data/ reports/ others/
```

## 公司说明

| 公司 | 英文名 | 主营产品 |
|------|--------|----------|
| 塞控电气 | safesav | 软启动器、变频器 |
| 昂瑞机械 | angrui | 气动元器件 |

## 平台覆盖

- alibaba（阿里国际站）
- aliexpress（速卖通）
- mic（made-in-china.com）
- taobao（淘宝）
- 1688

## 文档规范

- **data**：原始导出数据（Excel、CSV 等），按平台+日期归档
- **reports**：定期（月/季度）汇总分析报告，含图表与结论
- **others**：流程文档、竞品分析、会议纪要等辅助材料

## 命名规范

`YYYY-MM-DD_平台_内容简述.ext`

示例：`2026-03-15_alibaba_inquiry.xlsx`

---
*最后更新：2026-04-11*

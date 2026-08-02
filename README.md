# Company Card — 企业认知主页

> 价值投资闭环系统的企业认知档案库。每个企业一个目录，Git 提供版本管理。

## 目录结构

```
company_card/
├── README.md
├── [公司名]/
│   ├── 企业主页.md                  # 三支柱16节点认知主页（当前最新版）
│   ├── autoresearch/                # 自主研究产出
│   ├── 财报分析/                    # financial-analysis 产出
│   ├── 价值投资分析/                # value-investing-analysis 产出
│   ├── 估值/                        # greenwald-valuation 产出
│   ├── 种子清单/                    # autoresearch 种子清单
│   └── 调研资料/                    # 补充调研材料
```

## 与 ima 知识库的关系

| 维度 | ima KB | GitHub |
|------|--------|--------|
| 版本管理 | 每次上传新版本，旧版本累积 | Git 原生版本控制，直接更新源文件 |
| 用途 | 检索分发 + 跨 skill 搜索 | 版本管理 + 结构化存储 + 变更追踪 |

GitHub 中的文件不带版本号（如 `企业主页.md`），Git history 即版本管理。
ima KB 中保留带版本号的文件（如 `企业主页_[公司]_v3.md`），用于检索。

## 说明

- 通过 Deploy Key 认证，仅授权 `company_card` 仓库
- 由 company-card skill 自动同步管理

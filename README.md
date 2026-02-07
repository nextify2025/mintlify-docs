# 金融数据文档

专业的金融市场数据与量化交易文档中心。

## 内容板块

- **股票**: A股市场数据、交易日历、指数行情、研究报告
- **期货**: 商品期货、金融期货行情与分析
- **期权**: 期权定价、Greeks、波动率分析
- **宏观**: 美国、欧洲、中国、日本等主要经济体数据
- **量化**: PTrade、QMT 量化交易平台接入
- **黄金**: 贵金属行情、供需分析
- **工具**: 数据接口、分析工具、开发资源

## 本地开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

启动本地预览:

```bash
mint dev
```

访问 `http://localhost:3000`

## 目录结构

```
├── stocks/          # 股票
│   ├── calendar/    # 交易日历
│   ├── indices/     # 指数数据
│   ├── reports/     # 研究报告
│   └── screener/    # 选股器
├── futures/         # 期货
│   ├── commodity/   # 商品期货
│   └── financial/   # 金融期货
├── options/         # 期权
├── macro/           # 宏观经济
│   ├── usa/         # 美国
│   ├── eu/          # 欧洲
│   ├── china/       # 中国
│   └── japan/       # 日本
├── quant/           # 量化交易
│   ├── ptrade/      # PTrade
│   └── qmt/         # QMT
├── gold/            # 贵金属
├── tools/           # 工具
└── about/           # 关于
```

## 免责声明

本文档仅供学习和参考，不构成任何投资建议。

# CashLog 项目文档

## 项目概述

CashLog 是一个iOS应用项目，主要功能是帮助用户记录现金流。该项目包含了丰富的资源文件，包括应用图标、字体、主题配置和隐私政策等。

## 目录结构

```
CashLog/
├── resources/              # 资源目录
│   ├── app/               # 应用相关资源
│   │   ├── easylife.jpg   # EasyLife应用图标
│   │   ├── list.json      # 应用列表配置文件
│   │   ├── oriode.png     # Oriode应用图标
│   │   └── sportimer.jpg  # Sport Timer应用图标
│   ├── font/              # 字体文件目录
│   │   ├── *.ttf         # 各种中文字体文件
│   │   ├── *.otf         # OpenType字体文件
│   │   ├── *.pdf         # 字体预览文件
│   │   ├── *.d/          # 字体分片目录
│   │   ├── zh.json       # 中文字体配置文件
│   │   └── 春夏秋行楷授权说明.pdf  # 字体授权说明文档
│   ├── privacy/           # 隐私政策目录
│   │   ├── privacy-en.txt # 英文隐私政策
│   │   └── privacy-zh.txt # 中文隐私政策
│   └── theme/             # 主题配置目录
│       ├── *.json        # 各种主题配置文件
│       └── sources.json  # 主题源配置
├── .gitignore            # Git忽略文件配置
├── README.md             # 项目说明文档
└── info.md               # 项目文档（本文件）
```

## 详细说明

### resources/app/

应用相关资源目录，包含三个应用的配置和图标：

- **EasyLife（米老虎）**：各种小工具，APP届的瑞士军刀，无广告，可免费下载使用，可不联网使用
- **Oriode（箴曰）**：一个每天推送鸡汤的小应用
- **Sport Timer（运动计时器）**：帮助用户进行运动计时

### resources/font/

字体文件目录，包含13种中文字体：

1. **悠然小楷** (slideyouran-Regular.ttf)
2. **志莽行书** (ZhiMangXing-Regular.ttf)
3. **鸿雷拙书简体** (SlideHongLeiZhuo-Regular.otf)
4. **春风楷** (Slidechunfeng-Regular.ttf)
5. **夏行楷** (Slidexiaxing-Regular.ttf)
6. **秋鸿楷** (Slideqiuhong-Regular.ttf)
7. **江西拙楷** (SlideJiangXiZhuo-Regular.ttf)
8. **演示佛系体** (Slidefu-Regular.ttf)
9. **临海隶书** (LinHaiLiShu-Regular.ttf)
10. **贤二体** (Xianeti-Regular.ttf)
11. **青松手写体** (QingSongWritter-Regular.ttf)
12. **庞门正道粗书体** (PangMenBold-Regular.ttf)
13. **沐瑶软笔手写体** (MuYaoSoftWritter-Regular.ttf)

每个字体都包含完整的元数据（名称、文件名、大小、MD5值和授权信息）。

### resources/privacy/

隐私政策目录，包含中英文版本的隐私政策文件，详细说明了：
- 适用范围
- 信息的使用
- 信息披露
- 信息存储和交换
- 信息安全

### resources/theme/

主题配置目录，包含多个主题配置文件：
- first.json, second.json, third.json 等
- deepseek-girl.json（深色主题）
- sources.json（主题源配置）

每个主题文件定义了各种颜色配置，包括：
- 背景色（background）
- 主色调（primary, secondary）
- 字体颜色（font, primary_font等）
- 列表样式（listBackground, listItemFont等）
- 按钮样式（btn_font）
- 各种颜色（green, red, blue, orange, purple, cyan, yellow, gray）

## 技术栈

- **平台**：iOS
- **配置格式**：JSON
- **字体格式**：TTF, OTF
- **文档格式**：Markdown

## 注意事项

- 所有字体文件都包含授权信息，使用时请遵守相应的授权协议
- 隐私政策文件包含中英文两个版本，确保符合不同地区的要求
- 主题配置文件定义了完整的颜色方案，支持自定义主题

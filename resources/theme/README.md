# 主题配置说明

## 概述

本目录包含CashLog应用的所有主题配置文件。每个主题JSON文件定义了一套完整的颜色方案，用于控制应用的外观和视觉效果。

## 主题列表

| 主题文件 | 主题名称 | 颜色风格 | 背景色 | 主色调 | 辅助色 | 特点 | 适用场景 |
|---------|---------|---------|--------|--------|--------|------|---------|
| first.json | 温暖米色主题 | 温暖柔和的米色调 | #F6F3E8 | #83A2FF | #D2DFFF | 整体色调温暖舒适 | 通用主题，适合大多数用户 |
| second.json | 深蓝灰色主题 | 沉稳的深蓝灰色调 | #E4E4E4 | #4C6B89 | #DDDBCE | 色调沉稳专业，商务感强 | 商务环境，需要专业感的场景 |
| third.json | 粉色浪漫主题 | 柔和的粉色系 | #F4E0EA | #E676A7 | #F1B3CD | 浪漫温馨，女性化设计 | 女性用户，追求浪漫氛围 |
| fouth.json | 大地色系主题 | 自然的大地色调 | #EFE7DD | #8D5966 | #D8CDBC | 自然舒适，回归自然 | 喜欢自然风格的用户 |
| fifth.json | 明亮黄色主题 | 活泼明亮的黄色调 | #FFFFFF | #FDCF31 | #F2E179 | 明亮活泼，充满活力 | 需要活力和积极氛围的场景 |
| sixth.json | 清新绿色主题 | 清新的绿色系 | #FFFFFF | #1E7D5C | #D8E5B1 | 清新自然，护眼舒适 | 长时间使用，需要护眼的场景 |
| seven.json | 深色主题 | 经典的深色模式 | #000000 | #8571CF | #131313 | 深色模式，减少眼部疲劳 | 夜间使用，深色模式爱好者 |
| eight.json | 暗黑主题 | 极致的暗黑风格 | #000000 | #2F375A | #413838 | 极致暗黑，对比度高 | 追求极致暗黑体验的用户 |
| ninth.json | 中国红主题 | 中国红金色系 | #FDFDFD | #A9C9C9 | #DDDBCE | 中国风配色，含蓄典雅 | 喜欢中国风的用户 |
| tenth.json | 暗色红主题 | 暗色红色系 | #F4F3F1 | #C2002B | #FBAF5B | 暗色调配红色，对比强烈 | 喜欢强烈对比的用户 |
| deepseek-girl.json | 粉色少女主题 | 可爱的粉色系 | #FFF5F5 | #FF69B4 | #FFD1E0 | 少女心十足，可爱活泼 | 年轻女性用户，追求可爱风格 |
| deepseek-girl.dark.json | 深色粉色主题 | 深色粉色系 | #1A1215 | #FF6B9D | #3F2832 | 深色模式配粉色，时尚个性 | 夜间使用，喜欢深色粉色的用户 |

## 主题文件格式说明

### 基本结构

主题文件采用JSON格式，包含以下几类颜色配置：

#### 1. 基础颜色

| 字段 | 说明 | 示例 |
|------|------|------|
| `background` | 应用背景色 | `"#F6F3E8"` |
| `font` | 主要文字颜色，用于background和block作为背景时的文字 | `"#161A30"` |
| `block` | 块元素背景色 | `"#FEF8E8"` |

#### 2. 主色调

| 字段 | 说明 | 示例 |
|------|------|------|
| `primary` | 主色调 | `"#83A2FF"` |
| `primary_font` | primary作为背景时的文字颜色 | `"#FEFEFE"` |
| `secondary` | 辅助色 | `"#D2DFFF"` |
| `secondary_font` | secondary作为背景时的文字颜色 | `"#161A30"` |

#### 3. 列表样式

| 字段 | 说明 | 示例 |
|------|------|------|
| `listBackground` | 列表背景色 | `"#D2DFFF"` |
| `listItemBackground` | 列表项背景色 | `"#F6F3E8"` |
| `listItemFont` | 列表项文字颜色，用于listBackground和listItemBackground作为背景时的文字 | `"#000000"` |

#### 4. 功能颜色

| 字段 | 说明 | 示例 |
|------|------|------|
| `red` | 红色（警告/错误） | `"#FA7070"` |
| `red_font` | red作为背景时的文字颜色 | `"#FFFFFF"` |
| `orange` | 橙色（提示） | `"#F3B664"` |
| `orange_font` | orange作为背景时的文字颜色 | `"#161A30"` |
| `yellow` | 黄色（注意） | `"#CAC011"` |
| `yellow_font` | yellow作为背景时的文字颜色 | `"#161A30"` |
| `green` | 绿色（成功） | `"#9FBB73"` |
| `green_font` | green作为背景时的文字颜色 | `"#FFFFFF"` |
| `blue` | 蓝色（信息） | `"#B4BDFF"` |
| `blue_font` | blue作为背景时的文字颜色 | `"#161A30"` |
| `purple` | 紫色（特殊） | `"#C683D7"` |
| `purple_font` | purple作为背景时的文字颜色 | `"#FFFFFF"` |
| `cyan` | 青色（信息） | `"#9AD0C2"` |
| `cyan_font` | cyan作为背景时的文字颜色 | `"#161A30"` |
| `gray` | 灰色（禁用/次要） | `"#4E4E4E"` |
| `gray_font` | gray作为背景时的文字颜色 | `"#FFFFFF"` |
| `pink` | 粉色（功能色，与其他功能颜色red、orange、yellow、green、blue、purple、cyan、gray同类） | `"#FFB4D8"` |
| `pink_font` | pink作为背景时的文字颜色 | `"#161A30"` |

#### 5. 扩展功能颜色

| 字段 | 说明 | 示例 |
|------|------|------|
| `success` | 成功状态 | `"#39AD4E"` |
| `success_font` | success作为背景时的文字颜色 | `"#FFFFFF"` |
| `danger` | 危险状态 | `"#E76D5E"` |
| `danger_font` | danger作为背景时的文字颜色 | `"#FFFFFF"` |
| `warning` | 警告状态 | `"#E9AA68"` |
| `warning_font` | warning作为背景时的文字颜色 | `"#161A30"` |

#### 6. 奖牌颜色

| 字段 | 说明 | 示例 |
|------|------|------|
| `golden` | 金牌颜色（第一名） | `"#FFD700"` |
| `golden_font` | golden作为背景时的文字颜色 | `"#161A30"` |
| `silver` | 银牌颜色（第二名） | `"#C0C0C0"` |
| `silver_font` | silver作为背景时的文字颜色 | `"#161A30"` |
| `bronze` | 铜牌颜色（第三名） | `"#CD7F32"` |
| `bronze_font` | bronze作为背景时的文字颜色 | `"#FFFFFF"` |

#### 7. 按钮样式

| 字段 | 说明 | 示例 |
|------|------|------|
| `btn_font` | 通用按钮文字颜色，一般被功能色、奖牌色、block作为按钮背景色时使用 | `"#FEFEFE"` |

### 颜色使用规则

#### 背景颜色分类

可以作为背景的颜色包括：

1. **基础背景色**
   - `background` - 应用主背景
   - `block` - 块元素背景
   - `listBackground` - 列表背景
   - `listItemBackground` - 列表项背景

2. **主题色**
   - `primary` - 主色调
   - `secondary` - 辅助色

3. **功能颜色**
   - `red` - 红色
   - `orange` - 橙色
   - `yellow` - 黄色
   - `green` - 绿色
   - `blue` - 蓝色
   - `purple` - 紫色
   - `cyan` - 青色
   - `gray` - 灰色
   - `pink` - 粉色

4. **扩展功能颜色**
   - `success` - 成功
   - `danger` - 危险
   - `warning` - 警告

5. **奖牌颜色**
   - `golden` - 金牌
   - `silver` - 银牌
   - `bronze` - 铜牌

#### 文字颜色对应关系

每个背景颜色都有对应的文字颜色：

| 背景颜色 | 对应文字颜色 |
|----------|--------------|
| `background` | `font` |
| `block` | `font` |
| `listBackground` | `listItemFont` |
| `listItemBackground` | `listItemFont` |
| `primary` | `primary_font` |
| `secondary` | `secondary_font` |
| `red` | `red_font` |
| `orange` | `orange_font` |
| `yellow` | `yellow_font` |
| `green` | `green_font` |
| `blue` | `blue_font` |
| `purple` | `purple_font` |
| `cyan` | `cyan_font` |
| `gray` | `gray_font` |
| `pink` | `pink_font` |
| `success` | `success_font` |
| `danger` | `danger_font` |
| `warning` | `warning_font` |
| `golden` | `golden_font` |
| `silver` | `silver_font` |
| `bronze` | `bronze_font` |

#### 默认文字颜色规则

功能颜色（包括奖牌色）的文字颜色如果缺少或为空字符串 `""`，则会使用 `btn_font` 代替。

### 颜色格式规范

所有颜色值必须使用十六进制格式，格式为 `#RRGGBB`，其中：
- RR：红色分量（00-FF）
- GG：绿色分量（00-FF）
- BB：蓝色分量（00-FF）

示例：
- `"#FFFFFF"` - 白色
- `"#000000"` - 黑色
- `"#FF0000"` - 红色
- `"#00FF00"` - 绿色
- `"#0000FF"` - 蓝色

### 可选字段说明

某些字段在某些主题中可能为空字符串 `""`，表示该字段未定义或使用默认值。在实际使用时，应用会根据需要使用默认颜色或继承其他颜色。

### 完整示例

```json
{
  "background": "#F6F3E8",
  "font": "#161A30",
  "block": "#FEF8E6",
  "primary": "#83A2FF",
  "primary_font": "#FEFEFE",
  "secondary": "#D2DFFF",
  "secondary_font": "#161A30",
  "listBackground": "#D2DFFF",
  "listItemBackground": "#F6F3E8",
  "listItemFont": "#000000",
  "red": "#FA7070",
  "red_font": "#FFFFFF",
  "orange": "#F3B664",
  "orange_font": "#161A30",
  "yellow": "#CAC011",
  "yellow_font": "#161A30",
  "green": "#9FBB73",
  "green_font": "#FFFFFF",
  "blue": "#B4BDFF",
  "blue_font": "#161A30",
  "purple": "#C683D7",
  "purple_font": "#FFFFFF",
  "cyan": "#9AD0C2",
  "cyan_font": "#161A30",
  "gray": "#4E4E4E",
  "gray_font": "#FFFFFF",
  "pink": "#FFB4D8",
  "pink_font": "#161A30",
  "success": "#39AD4E",
  "success_font": "#FFFFFF",
  "danger": "#E76D5E",
  "danger_font": "#FFFFFF",
  "warning": "#E9AA68",
  "warning_font": "#161A30",
  "golden": "#FFD700",
  "golden_font": "#161A30",
  "silver": "#C0C0C0",
  "silver_font": "#161A30",
  "bronze": "#CD7F32",
  "bronze_font": "#FFFFFF",
  "btn_font": "#FEFEFE"
}
```

**说明**：
- 所有主题建议都应该具有完整的颜色列表
- 功能颜色（包括奖牌色）的文字颜色如果缺少或为空字符串 `""`，则会使用 `btn_font` 代替
- 奖牌颜色设计时应考虑其意义：
  - `golden` - 金牌颜色，代表第一名，使用金色
  - `silver` - 银牌颜色，代表第二名，使用银色
  - `bronze` - 铜牌颜色，代表第三名，使用铜色

## 创建自定义主题

### 步骤1：复制现有主题

建议从现有的主题文件复制一个作为模板，例如：

```bash
cp first.json my-theme.json
```

### 步骤2：修改颜色值

根据您的需求修改JSON文件中的颜色值。建议使用在线颜色选择器工具来选择合适的颜色。

### 步骤3：测试主题

在应用中加载新主题，检查视觉效果是否满意。

### 步骤4：注册主题（可选）

如果需要在主题列表中显示您的主题，可以在 `sources.json` 文件中添加主题信息：

```json
{
  "name": "my-theme",
  "title": "My Custom Theme",
  "author": "Your Name",
  "summary": "A brief description of your theme"
}
```

## 设计建议

### 配色原则

1. **对比度**：确保文字颜色与背景色有足够的对比度，保证可读性
2. **一致性**：保持颜色方案的一致性，不要使用过多不同的颜色
3. **情感表达**：根据主题的情感定位选择合适的颜色
4. **可访问性**：考虑色盲用户的需求，避免仅依靠颜色传达信息

### 常见配色方案

1. **单色方案**：使用同一色相的不同明度和饱和度
2. **互补色方案**：使用色轮上相对的颜色
3. **三色方案**：使用色轮上等距的三个颜色
4. **类比色方案**：使用色轮上相邻的颜色

### 颜色心理学

- **红色**：热情、紧急、警告
- **橙色**：活力、友好、创意
- **黄色**：快乐、乐观、注意
- **绿色**：自然、成长、成功
- **蓝色**：信任、专业、冷静
- **紫色**：神秘、优雅、创意
- **粉色**：浪漫、温柔、可爱、少女心
- **青色**：清新、平静、和谐
- **灰色**：中性、稳重、低调
- **金色**：高贵、荣耀、胜利
- **银色**：纯洁、优雅、现代
- **铜色**：稳重、传统、荣誉

## 注意事项

1. 所有JSON文件必须符合有效的JSON格式
2. 颜色值必须使用十六进制格式
3. 字段名必须使用英文，区分大小写
4. 建议使用代码编辑器编辑JSON文件，确保格式正确
5. 修改主题前建议备份原始文件

## 相关文件

- `sources.json`：主题列表配置文件，包含所有主题的元数据信息

## 版本信息

当前主题配置版本：1.08

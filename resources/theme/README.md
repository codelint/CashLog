# Theme Configuration Guide

## Overview

This directory contains all theme configuration files for the CashLog application. Each theme JSON file defines a complete color scheme used to control the appearance and visual effects of the application.

## Theme List

| Theme File | Theme Name | Primary Color | Features | Use Case |
|------------|-----------|---------------|----------|----------|
| first.json | Warm Beige Theme | #83A2FF | Warm and comfortable overall tone | General theme, suitable for most users |
| second.json | Deep Blue-Gray Theme | #4C6B89 | Calm and professional, strong business feel | Business environments, scenarios requiring professionalism |
| third.json | Pink Romantic Theme | #E676A7 | Romantic and warm, feminine design | Female users, pursuing a romantic atmosphere |
| fouth.json | Earth Tone Theme | #8D5966 | Natural and comfortable, back to nature | Users who prefer natural styles |
| fifth.json | Bright Yellow Theme | #FDCF31 | Bright and lively, full of vitality | Scenarios needing energy and positive atmosphere |
| sixth.json | Fresh Green Theme | #1E7D5C | Fresh and natural, eye-friendly and comfortable | Long-term use, scenarios needing eye protection |
| seven.json | Dark Theme | #8571CF | Dark mode, reduces eye fatigue | Nighttime use, dark mode enthusiasts |
| eight.json | Dark Black Theme | #2F375A | Extreme dark, high contrast | Users pursuing ultimate dark mode experience |
| ninth.json | Chinese Red Theme | #A9C9C9 | Chinese style colors, subtle and elegant | Users who like Chinese style |
| tenth.json | Dark Red Theme | #C2002B | Dark tone with red, strong contrast | Users who like strong contrast |
| deepseek-girl.json | Pink Girly Theme | #FF69B4 | Full of girly heart, cute and lively | Young female users, pursuing cute style |
| deepseek-girl.dark.json | Dark Pink Theme | #FF6B9D | Dark mode with pink, stylish and personalized | Nighttime use, users who like dark pink |
| social.json | Social Theme | #1877F2 | Facebook style, clean and modern, friendly and beautiful | Social application scenarios, users who like Facebook style design |

## Theme File Format Description

### Basic Structure

Theme files use JSON format and contain the following categories of color configurations:

#### 1. Base Colors

| Field | Description | Example |
|------|-------------|---------|
| `background` | Application background color | `"#F6F3E8"` |
| `font` | Main text color, used for text when background and block are backgrounds | `"#161A30"` |
| `block` | Block element background color | `"#FEF8E8"` |

#### 2. Primary Colors

| Field | Description | Example |
|------|-------------|---------|
| `primary` | Primary color | `"#83A2FF"` |
| `primary_font` | Text color when primary is used as background | `"#FEFEFE"` |
| `secondary` | Secondary color | `"#D2DFFF"` |
| `secondary_font` | Text color when secondary is used as background | `"#161A30"` |

#### 3. List Styles

| Field | Description | Example |
|------|-------------|---------|
| `listBackground` | List background color | `"#D2DFFF"` |
| `listItemBackground` | List item background color | `"#F6F3E8"` |
| `listItemFont` | List item text color, used for text when listBackground and listItemBackground are backgrounds | `"#000000"` |

#### 4. Functional Colors

| Field | Description | Example |
|------|-------------|---------|
| `red` | Red (warning/error) | `"#FA7070"` |
| `red_font` | Text color when red is used as background | `"#FFFFFF"` |
| `orange` | Orange (hint) | `"#F3B664"` |
| `orange_font` | Text color when orange is used as background | `"#161A30"` |
| `yellow` | Yellow (attention) | `"#CAC011"` |
| `yellow_font` | Text color when yellow is used as background | `"#161A30"` |
| `green` | Green (success) | `"#9FBB73"` |
| `green_font` | Text color when green is used as background | `"#FFFFFF"` |
| `blue` | Blue (information) | `"#B4BDFF"` |
| `blue_font` | Text color when blue is used as background | `"#161A30"` |
| `purple` | Purple (special) | `"#C683D7"` |
| `purple_font` | Text color when purple is used as background | `"#FFFFFF"` |
| `cyan` | Cyan (information) | `"#9AD0C2"` |
| `cyan_font` | Text color when cyan is used as background | `"#161A30"` |
| `gray` | Gray (disabled/secondary) | `"#4E4E4E"` |
| `gray_font` | Text color when gray is used as background | `"#FFFFFF"` |
| `pink` | Pink (functional color, same category as other functional colors red, orange, yellow, green, blue, purple, cyan, gray) | `"#FFB4D8"` |
| `pink_font` | Text color when pink is used as background | `"#161A30"` |

#### 5. Extended Functional Colors

| Field | Description | Example |
|------|-------------|---------|
| `success` | Success state | `"#39AD4E"` |
| `success_font` | Text color when success is used as background | `"#FFFFFF"` |
| `danger` | Danger state | `"#E76D5E"` |
| `danger_font` | Text color when danger is used as background | `"#FFFFFF"` |
| `warning` | Warning state | `"#E9AA68"` |
| `warning_font` | Text color when warning is used as background | `"#161A30"` |

#### 6. Medal Colors

| Field | Description | Example |
|------|-------------|---------|
| `golden` | Gold medal color (first place) | `"#FFD700"` |
| `golden_font` | Text color when golden is used as background | `"#161A30"` |
| `silver` | Silver medal color (second place) | `"#C0C0C0"` |
| `silver_font` | Text color when silver is used as background | `"#161A30"` |
| `bronze` | Bronze medal color (third place) | `"#CD7F32"` |
| `bronze_font` | Text color when bronze is used as background | `"#FFFFFF"` |

#### 7. Button Styles

| Field | Description | Example |
|------|-------------|---------|
| `btn_font` | Universal button text color, generally used when functional colors, medal colors, and block are used as button background colors | `"#FEFEFE"` |

### Color Usage Rules

#### Background Color Categories

Colors that can be used as backgrounds include:

1. **Base Background Colors**
   - `background` - Application main background
   - `block` - Block element background
   - `listBackground` - List background
   - `listItemBackground` - List item background

2. **Theme Colors**
   - `primary` - Primary color
   - `secondary` - Secondary color

3. **Functional Colors**
   - `red` - Red
   - `orange` - Orange
   - `yellow` - Yellow
   - `green` - Green
   - `blue` - Blue
   - `purple` - Purple
   - `cyan` - Cyan
   - `gray` - Gray
   - `pink` - Pink

4. **Extended Functional Colors**
   - `success` - Success
   - `danger` - Danger
   - `warning` - Warning

5. **Medal Colors**
   - `golden` - Gold medal
   - `silver` - Silver medal
   - `bronze` - Bronze medal

#### Text Color Correspondence

Each background color has a corresponding text color:

| Background Color | Corresponding Text Color |
|------------------|--------------------------|
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

#### Default Text Color Rule

If the text color for functional colors (including medal colors) is missing or an empty string `""`, `btn_font` will be used instead.

### Color Format Specification

All color values must use hexadecimal format, in the format `#RRGGBB`, where:
- RR: Red component (00-FF)
- GG: Green component (00-FF)
- BB: Blue component (00-FF)

Examples:
- `"#FFFFFF"` - White
- `"#000000"` - Black
- `"#FF0000"` - Red
- `"#00FF00"` - Green
- `"#0000FF"` - Blue

### Optional Field Description

Some fields in some themes may be empty strings `""`, indicating that the field is undefined or uses default values. In actual use, the application will use default colors or inherit other colors as needed.

### Complete Example

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

**Note**:
- All themes are recommended to have a complete color list
- If the text color for functional colors (including medal colors) is missing or an empty string `""`, `btn_font` will be used instead
- When designing medal colors, consider their meaning:
  - `golden` - Gold medal color, representing first place, using gold
  - `silver` - Silver medal color, representing second place, using silver
  - `bronze` - Bronze medal color, representing third place, using bronze

## Creating Custom Themes

### Step 1: Copy Existing Theme

It is recommended to copy an existing theme file as a template, for example:

```bash
cp first.json my-theme.json
```

### Step 2: Modify Color Values

Modify the color values in the JSON file according to your needs. It is recommended to use online color picker tools to select appropriate colors.

### Step 3: Test Theme

Load the new theme in the application and check if the visual effect is satisfactory.

### Step 4: Register Theme (Optional)

If you need to display your theme in the theme list, you can add theme information in the `sources.json` file:

```json
{
  "name": "my-theme",
  "title": "My Custom Theme",
  "author": "Your Name",
  "summary": "A brief description of your theme"
}
```

## Design Recommendations

### Color Principles

1. **Contrast**: Ensure sufficient contrast between text color and background color to guarantee readability
   - For light backgrounds (such as yellow, cyan, purple, gray and other light tones), dark text must be used (such as `#2A2A2A`, `#231816`, `#3A2A20`, etc.)
   - Avoid using light or medium-depth text on light backgrounds, which will make text difficult to read
   - Common error examples:
     - Yellow background `#F2DD26` with light beige text `#FEF8E6` (extremely low contrast)
     - Cyan background `#9AD0C2` with gray text `#6F7E92` (relatively low contrast)
     - Purple background `#EE82EE` with gray text `#6F7E92` (relatively low contrast)
   - Recommended practices:
     - Use dark text on light backgrounds (black series, dark gray series, dark brown series)
     - Use light text on dark backgrounds (white series, light gray series)
     - Refer to existing theme color schemes to ensure contrast meets readability standards

2. **Consistency**: Maintain consistency in the color scheme, do not use too many different colors
3. **Emotional Expression**: Choose appropriate colors according to the emotional positioning of the theme
4. **Accessibility**: Consider the needs of color-blind users, avoid relying solely on color to convey information

### Common Color Schemes

1. **Monochromatic Scheme**: Use different brightness and saturation of the same hue
2. **Complementary Color Scheme**: Use opposite colors on the color wheel
3. **Triadic Scheme**: Use three equally spaced colors on the color wheel
4. **Analogous Color Scheme**: Use adjacent colors on the color wheel

### Color Psychology

- **Red**: Passion, urgency, warning
- **Orange**: Energy, friendliness, creativity
- **Yellow**: Happiness, optimism, attention
- **Green**: Nature, growth, success
- **Blue**: Trust, professionalism, calmness
- **Purple**: Mystery, elegance, creativity
- **Pink**: Romance, gentleness, cuteness, girly heart
- **Cyan**: Freshness, calmness, harmony
- **Gray**: Neutrality, stability, low-key
- **Golden**: Nobility, glory, victory
- **Silver**: Purity, elegance, modernity
- **Bronze**: Stability, tradition, honor

## Important Notes

1. All JSON files must conform to valid JSON format
2. Color values must use hexadecimal format
3. Field names must use English and are case-sensitive
4. It is recommended to use a code editor to edit JSON files to ensure correct formatting
5. It is recommended to back up original files before modifying themes
6. **Must update update_time field when updating sources.json**:
   - The `update_time` field should be filled with the current timestamp (Unix timestamp, in seconds)
   - Methods to get timestamp:
     - macOS/Linux: `date +%s`
     - Windows: `powershell -Command "[int][double]::Parse((Get-Date -UFormat %s))"`
     - Online tool: https://www.unixtimestamp.com/
   - Example: `"update_time": 1766995701`
   - **Important**: Every time you modify sources.json or sources.zh.json, you must synchronously update the update_time field to the current timestamp, otherwise theme updates may not be correctly recognized by the application

## Related Files

- `sources.json`: Theme list configuration file, containing metadata information for all themes

## Version Information

Current theme configuration version: 1.10

**Update Notes**:
- v1.10: Added social theme, adopting Facebook design style, using iconic blue primary color and clean social media design; added update_time field usage instructions, reminding developers to synchronize timestamp updates when updating theme list
- v1.09: Enhanced color principle description, detailed explanation of contrast requirements between text color and background color, avoiding readability issues when designing new themes

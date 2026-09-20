# Effect HUD

在屏幕显示当前玩家效果状态

![Effect HUD](./img/effecthud.png)

## Feature

- 可选 是否在打开 GUI 时隐藏
- 文本 颜色/阴影/对齐模式/间距 可调整
- 可选 横向/纵向显示
- 渲染尺寸/偏移 可调整

## Command

### `/eveffecthud <option>`

- `toggle` — 切换开关
- `gui` — 是否在打开 GUI 时隐藏
- `color <value>` — 文本颜色 (16进制 ARGB 字符串)
- `shadow` — 是否渲染文本阴影
- `vertical` — 是否纵向显示
- `align` — 切换对齐方式
- `spacing <value>` — 文字渲染间距
- `scale <value>` — 渲染尺寸
- `xoffset <value>` / `yoffset <value>` — 渲染位置偏移

## Configuration

### `effecthud`

- `enabled`, `hideWhenGuiOpen`, `shadow`, `vertical` — booleans
- `scale`, `xoffset`, `yoffset` — floats
- `color` — String
- `textAlgin`, `textSpacing` — ints
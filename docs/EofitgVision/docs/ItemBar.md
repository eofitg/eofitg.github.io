# Item Bar

显示周围玩家的背包物品信息条

![Item Bar](./img/itembar.png)

## Feature

- 可选 自己的是否显示
- 可选 隐身/蹲下时是否显示
- 可选 是否永远面向玩家
- 可选 横向/纵向显示
- 渲染距离/偏移/尺寸可调整

## Command

### `/evitembar <option>`

- `toggle` — 切换开关
- `self` — 是否显示自己的
- `invis` — 隐身是否隐藏
- `sneak` — 蹲下是否隐藏
- `face` — HUD是否永远面向玩家
- `shadow` — 是否渲染文本阴影
- `vertical` — 是否纵向显示
- `distance <value>` — 最大渲染距离
- `scale <value>` — 渲染尺寸
- `xoffset <value>` / `yoffset <value>` / `zoffset <value>` — 渲染位置偏移
- `add <value>` / `remove <value>` — 添加/移除需检查的物品

## Configuration

### `itembar`

- `enabled`, `showSelf`, `hideWhenInvisible`, `hideWhenSneaking`, `facePlayer`, `vertical` — booleans
- `maxDistance`, `scale`, `xOffset`, `yOffset`, `zOffset` — floats
- `itemList` — String List
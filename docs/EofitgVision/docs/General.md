# General

基础开关和全局功能

## Feature

- 全局切换开关
- 一键屏蔽争议/作弊功能
- 切换是否静默处理模块控制命令，即是否输出命令反馈
- 重载配置文件（手动修改 `eofitgvision.cfg` 后需执行）

## Command

### `/eofitgvision <option>`

- `toggle` — 全局开关
- `legit` — 合法模式开关
- `silent` — 静默处理模式开关
- `reload` — 重载配置文件

### `/evconfig <option>`

列出指定分类的全部配置项信息

- `general` / `healthbar` / `blockoverlay` / `firehud` / `enchantmentbar` / `hitbox` / `effecthud` / `effectbar` / `armorhud` / `arrowhud` / `breakoverlay` / `itemcounter` / `armorbar`

## Configuration

### `general`

- `enabled`, `legitMode`, `silentMode` — boolean
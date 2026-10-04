# 微信输入法风格皮肤 · 同文输入法（Trime）

仿微信输入法键盘的 Trime 主题，适配 Trime 3.3.x。

| 浅色                              | 深色                            |
| ------------------------------- | ----------------------------- |
| ![light](screenshots/light.png) | ![dark](screenshots/dark.png) |

## 特性

- 微信同款观感：白色圆角按键 + 底部阴影、灰色功能键、绿色回车 / 搜索键
- 浅色 / 深色两套配色，跟随系统自动切换
- Shift 三态（小写 / 大写 / 锁定）
- 按键长按提示：数字行、符号行、`x` `c` `v` 长按剪切 / 复制 / 粘贴、`a` 长按全选
- 回车键智能标签：搜索框显示「搜索」、普通输入显示「回车」、拼音未上屏显示「确定」
- 数字键盘 + 7 分类符号库（最近 / 中 / 英 / 《》 / 货币 / 数学 / 一二）

## 安装

1. 安装[同文输入法（Trime）](https://github.com/osfans/trime/releases)，并设为当前输入法
2. 把仓库文件复制到手机目录 `Android/data/com.osfans.trime/files/rime/`：
   - `trime-mint.trime.yaml`、`font.ttf` → 放到 `rime/` 下
   - `backgrounds/` 里的 6 张图片 → 放到 `rime/backgrounds/` 下
3. 打开 Trime 设置 → 键盘样式 → 主题 → 选择「微信输入法」
4. （可选）想跟随系统深浅模式：在 Trime 设置里打开「跟随系统深色」

## 字体

字体为 HarmonyOS Sans SC Black（华为发布的免费字体，可商用），重命名为 `font.ttf`。
不需要自定义字体时可删除，会自动回退到系统字体。



- 字体版权归华为所有，遵循其免费字体授权条款。



# Draw Steel 中文翻译模块

这是一个为 [Draw Steel](https://foundryvtt.com/packages/draw-steel) 系统提供中文（简体）翻译的 FoundryVTT 模块。

## 版本信息

- **适配版本**: Draw Steel 0.9.1
- **翻译类型**: 机器翻译版本
- **语言**: 简体中文 (cn)

## 安装方法

### 方法一：通过 Manifest URL 安装（推荐）

1. 在 FoundryVTT 中打开"添加模块"界面
2. 点击"安装模块"
3. 在"Manifest URL"中输入：
   ```
   https://raw.githubusercontent.com/SilverStreamAG/draw-steel-cn/main/module.json
   ```
4. 点击"安装"并等待完成
5. 在"管理模块"中启用该模块

### 方法二：手动安装

1. 下载或克隆此仓库
2. 将整个 `draw-steel-cn` 文件夹复制到 FoundryVTT 的 `modules/` 目录
3. 在 FoundryVTT 的"管理模块"中启用该模块

## 依赖要求

- **Babele**: 此模块需要 [Babele](https://foundryvtt.com/packages/babele) 模块才能正常工作
- **Draw Steel 系统**: 需要安装 Draw Steel 0.9.1 系统

## 功能说明

本模块提供以下内容的翻译：

- 能力 (Abilities)
- 角色选项 (Character Options)
- 职业 (Classes)
- 日志 (Journals)
- 怪物特性 (Monster Features)
- 怪物 (Monsters)
- 血统 (Origins)
- 奖励 (Rewards)
- 表格 (Tables)

## 重要提示

⚠️ **这是机器翻译版本**

- 翻译内容由机器自动生成，可能存在不准确或不通顺的地方
- 建议在使用过程中如发现翻译错误，可以手动修改翻译文件
- 翻译文件位于 `compendium/cn/` 目录下，为 JSON 格式

## 使用说明

1. 确保已安装并启用了 **Babele** 模块
2. 安装并启用本模块
3. 在游戏世界中，Babele 会自动应用翻译
4. 如果翻译未生效，请检查：
   - Babele 模块是否已启用
   - 本模块是否已启用
   - Draw Steel 系统版本是否为 0.9.1

## 贡献

欢迎提交 Issue 或 Pull Request 来改进翻译质量！

## 许可证

本项目遵循原 Draw Steel 系统的许可证。

## 更新日志

### 1.0.0
- 初始版本
- 适配 Draw Steel 0.9.1
- 提供完整的 Compendium 翻译
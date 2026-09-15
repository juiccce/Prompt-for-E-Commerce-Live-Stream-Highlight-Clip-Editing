# Prompt-for-E-Commerce-Live-Stream-Highlight-Clip-Editing
This is a prompt document for editing e-commerce women's cheongsam live-stream sales videos using GPT with embedded Codex. It contains keyword prompts for the new Chinese style, as well as listed prompts for cheongsam selling points.

## 一然旗袍可复用剪辑指令

版本日期：2026-09-13。内容整理自品牌对话、白月光试剪与用户反馈；本仓库保存可复用提示词，不是完整聊天备份。

### 文件导航

- [直播切片总指令](prompts/直播切片总指令.md)：品牌受众、卖点排序、开头、差异化、促单、成片规格与交付。
- [字幕与BGM操作指令](prompts/字幕与BGM操作指令.md)：剪映字号11实际校准、固定坐标、颜色阴影、音乐选段和混音。
- [封面设计指令](prompts/封面设计指令.md)：3:4参考封面、标题与品牌署名；字体未确认，位置与尺寸为估测。

### 换电脑后的使用方式

下载本仓库，准备本机视频和BGM素材，并将下面启动指令交给助手：

> 请先读取本仓库prompts目录中的《直播切片总指令》《字幕与BGM操作指令》《封面设计指令》，按最新已验收标准继续“一然旗袍”项目。本次产品为〈产品名称〉，素材位于〈本机素材路径〉，BGM库位于〈本机音乐文件夹〉，输出到〈输出路径〉；数量为〈数量，默认3–5条〉，每条〈默认17–27秒〉。请先确认本机素材可读、指定字体可用、剪映字号11校准依据可靠，再制作。字幕固定X=0、Y=-300；无法取得字体或校准依据时说明缺项，不猜测替换。需要封面时另按封面指令执行，区分正式验收值与参考估测值。

### 已验收与待校准

“白月光”8条修订版的字幕位置、字体、字号、颜色、阴影，以及BGM选段、音量已获用户确认。8条是该次任务数量，不是默认数量。字幕旧位置Y=-719已由Y=-300取代，字号11须通过剪映实际样片校准，不沿用旧渲染字号44。

封面指令来自1080×1440参考图，尚未制作验收。换电脑后重新确认字体、素材路径及校准条件。本仓库不包含视频、音乐、字体、临时文件或个人绝对路径；需要的素材应单独备份。保存到GitHub不会使助手自动记住内容，每次新任务先要求读取这些文件。

工具检查、实际试听和用户验收须分别记录；无法直接试听时不得声称已听过。

## Codex Skill

可安装版本位于 [`skills/yiran-qipao-live-clips`](skills/yiran-qipao-live-clips)。Skill入口只保留核心决策规则，详细的直播切片、字幕与BGM、封面规范放在其 `references/` 中，按任务需要读取。

换电脑后，可将整个 `yiran-qipao-live-clips` 文件夹复制到用户目录的 `.codex/skills/` 下，然后在任务中使用：

> 请使用 `$yiran-qipao-live-clips` 读取一然旗袍已验收标准，再处理本次直播素材。

安装后仍需重新确认本机素材路径、BGM路径、剪映油墨体或怀宋是否可用，以及字号11的校准依据。

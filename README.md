<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 013 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 013

### 把照片收藏进一张治愈水彩旅行票根

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种水彩收藏票根逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 一张横向票体 · 74/26 分区 · 治愈水彩 · 象牙白留白 · 本地化信息票根

XXD Panel 013 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它保留主体身份、轮廓、姿态与最有记忆点的必要环境，把这组关系重新概括为一张居中悬置的横向水彩票根，而不是把一个物体孤立地画出来。

票体内部严格约 74/26 左大右小：左侧以 2–4 个高明度、低至中等饱和度的相近色重译源图，右侧用目标语言的信息字段、编号与一枚克制圆章建立秩序。厚实哑光水彩纸、细密毛边、极轻投影和象牙白大留白让成品像被认真保存的旅行速写票据。

## 为什么需要 013

普通“水彩明信片”很容易变成满版通用风景、孤立物件、脏旧滤镜，或贴满邮戳与假坐标的电商模板，既失去源图关系，也失去编辑秩序。

013 的顺序完全相反：

```text
锁定主体与必要环境 → 保留至少三个源图识别线索 → 概括成一张居中横向票体 → 内部约 74/26 左景右票根 → 用 2–4 个相近治愈色重译水彩 → 主体稍清楚、环境自然减弱 → 让本地化字段、圆章与齿孔线服从同一网格
```

如果换成一张无关照片，水彩主体、必要环境、配色、字段含义、印章关系和文案仍然成立，这张图就不属于 013。

## 013 的视觉契约

- **主体与必要环境：** 至少三个源图专属线索保住身份、姿态、尺度、位置、地标与空间关系。
- **唯一横向票体：** 票体居中悬置在大面积象牙白中，不重复、不拼贴、不填满画布。
- **约 74/26 分区：** 左侧水彩明显更大，右侧信息票根紧凑，以精准竖向齿孔或撕票线分隔。
- **治愈水彩：** 2–4 个相近的高明度、低至中等饱和度源图色，纸白、晕染、干湿变化与少量颗粒清晰可见。
- **层次克制：** 主体稍清楚，远景和次要环境自然减弱，不做写实光影和复杂细节。
- **收藏纸感：** 厚实哑光水彩纸、细密锯齿或毛边、极轻自然接触投影，不做烧边和重度做旧。
- **信息网格：** 本地化字段、编号、短线、点列与一枚圆章沿统一左边线、基线和间距排列，绝不虚构事实。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090111918921158977) · 2026-08-19<br>
> GPT2 x 票根 x 明信片 x 邮戳 x 美学提示词 x VOL.013

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090111918921158977"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 013 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090111918921158977"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 013 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090111918921158977"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 013 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090111918921158977"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 013 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090111918921158977">查看原推文与完整提示词 →</a></p>

这些样张用于展示 013 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种输出共享同一种水彩收藏票根逻辑

四种模式支持单选或多选。可回复 `1`、`1+3`、`1、2、4` 或 `全部`；Skill 去重后按 1→4 执行。每种模式独立输出并进入独立子文件夹，不制作总图；`全部` 每张原图得到 7 个 PNG（前三种各 1 张＋壁纸 4 张）。尺寸可在同一回复中按模式标注，未标注普通模式按源图适配；文案默认跨所选模式共用，也可按模式单独指定。

| 模式 | 尺寸逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 | 上方完整原图，下方 013 水彩收藏票根；两块都保持原图完整尺寸，严格 50/50 |
| `left-right` | 源图自适应 | 左侧完整原图，右侧 013 水彩收藏票根；两块都保持原图完整尺寸，严格 50/50 |
| `design-only` | 源图自适应 | 只显示变化设计，不显示原照片；沿用原图比例和尺寸 |
| `wallpaper-pack` | 四种设备尺寸 | 分别输出手机、iPad、电脑、儿童手表四张 PNG |

用户精确尺寸 > 指定比例或用途 > 普通模式源图自适应。原始 `013.md` 里的 3:4 只是一开始的创作画幅，不会被写成当前 Skill 的静默默认值。

双联模式的摄影区域保持真实，只允许克制调色和必要的环境扩展。纯设计版与壁纸仍以照片为事实依据，但不显示原片。

### 四端壁纸：连贯或独立

壁纸没有静默尺寸默认。可选择常用预设——手机 `1440×3200`、iPad `2048×2732`、电脑 `3840×2160`、儿童手表 `1024×1024`——也可逐设备自定义。

- **连贯套装（推荐）：** 先生成并验收 iPad 定调图，另外三张都直接参考原照片＋同一张定调图，分别为设备重新构图。
- **四张独立：** 每张只参考原照片，可以探索不同的票体尺度、外部留白、水彩取景、治愈色盘、字段组合与印章关系。

连贯不等于裁切。四张壁纸始终分别生成、分别构图、分别验收，也不会按 iPad→手机→电脑→手表顺序垫图造成漂移。

## 文字是票根里的安静档案

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从源图可见或有依据的主体、时刻、状态、关系或情绪中提炼一个极短标题，再只选择真正有意义的少量字段。

DATE、PLACE、SUBJECT、MOMENT、FIELD、NO. 只是字段逻辑示例，字段名与字段值都跟随目标语言。日期、地点、坐标、路线、票号和旅行事件必须由用户提供或可靠确认；非旅行题材会改用对象、状态、项目、章节、季节、关系或情绪记录。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。票据字段名也会一起本地化，不会因为模板里常见 DATE 或 PLACE 就静默保留英语。

## 精确拼版交给代码，作品交给图像生成

图像模型负责源图绑定的主体—环境水彩、单张票体、74/26 分区、纸张毛边、齿孔线、信息网格、圆章和本地化文字。`scripts/compose_panel.py` 只负责画布规划、精确 50/50 位图拼合、最终尺寸和审计，不会用程序绘图伪造成品。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

精确上下画布的总高度必须为偶数，精确左右画布的总宽度必须为偶数。Skill 不会静默修改用户指定的像素。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-013.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-013" ~/.codex/skills/xxd-panel-013
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-013`。安装后重新启动 Agent 会话。

```text
$xxd-panel-013
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-013-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-013-prompt.en.md)
- [原始风格提示词](references/013-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-013/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-013-prompt.zh-CN.md
    ├── xxd-panel-013-prompt.en.md
    └── 013-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**不是给照片套旅行模板，而是把那段关系收藏成一张真正属于它的票。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>

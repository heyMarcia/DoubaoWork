<title comment-refs="c1 c2 c3 c4 c5 c6 c7 c8 c9 c10 c11 c12 c13 c14 c15 c16 c17 c18 c19 c20 c21 c22 c23 c24 c25 c26 c27 c28">OpenClaw 飞书官方插件使用指南（公开版） | OpenClaw Feishu Official Plugin User Guide (Public Version )</title>

<blockquote><p>An AI-translated English version is available for cross-language collaboration. (July 3, 2026, 13:07 GMT+8)</p><p>English version: <cite doc-id="WcHAdiZuXoAz1oxzRWhcFU1lnbd" file-type="docx" title="OpenClaw Feishu Official Plugin User Guide (Public Version )" type="doc"></cite></p></blockquote>

<callout comment-refs="c29 c30 c31 c32 c33 c34 c35 c36 c37 c38 c39 c40 c41 c42 c43 c44 c45 c46 c47 c48 c49 c50 c51 c52" emoji="‼️">
本插件目前处于快速迭代阶段，请谨慎尝试。为了提供更优质的用户体验，产品研发团队正在快速优化迭代，每天我们的龙虾插件都在变得更稳定、部署更简单、功能更好用。点击右上角... 关注文档更新。**🦞**
**飞书插件最新版本：2026.6.10｜**[**更新日志**](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#TXlPdfLFKoC4F9xtdOYci3I6n5d)
</callout>

## **重要更新：OpenClaw 飞书插件中一键安装** [**飞书CLI** ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) **能力**

![图片展示了飞书OpenClaw插件的相关信息。上方有飞书标志及“飞书OpenClaw插件”字样，强调全面支持飞书CLI。中间网址“open.feishu.cn/openclaw”被鼠标箭头指向。下方以数字形式呈现插件优势：15个模块、200+精选命令、22自带技能。底部说明支持按需选择用户身份或应用身份，能力更强、效果更稳、Token更省。该图与文档中介绍飞书插件支持一键安装飞书CLI的内容相关，直观呈现插件功能亮点。](https://feishu.cn/file/P8FDbjeGvo8IyoxlehkcyrpLn5d)

支持在OpenClaw 飞书插件中一键安装 [飞书CLI ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) 能力，安装后 飞书CLI 能力将自动绑定 OpenClaw 当前飞书机器人。

- 在飞书中体验更丰富全面的飞书操作能力，包括 消息与群组、云文档、云空间、电子表格、多维表格、日历、视频会议、妙记、邮箱、任务、知识库、通讯录、幻灯片、画板、OKR、审批、考勤
- 在安装时可以自由选择 OpenClaw 以什么方式与你协作：

  - 以机器人身份：AI将在飞书中以机器人的身份执行所有操作，适合作为团队助手,用于多人协作场景,如群聊问答、团队通知、公共文档维护。
  - 以你的身份：AI将在飞书中以你的名义执行所有操作，如读写文档、搜索消息、修改日程等，建议仅限个人使用。注意：该模式下请勿将此机器人分享给其他人使用,避免泄露你的飞书数据

> 温馨提示：如果你使用的是OpenClaw 中默认自带的飞书插件，也可以通过相同方式 使用   [飞书CLI ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) 能力



**安装方式：**

将以下内容 在飞书中 发送给OpenClaw 即可：

```Plain Text
请按照该文档帮我安装飞书cli：https://open.feishu.cn/document/mcp_open_tools/feishu-cli/set-up-lark-cli-for-ai-agents-in-openclaw_hermes.md
```





# 让你的飞书长出龙虾钳 **🦞**

> **飞书**[**现已支持一键部署 OpenClaw**](http://openclaw.feishu.cn)**，并自带本文介绍的飞书官方插件；**[火山引擎 ArkClaw](https://www.volcengine.com/activity/codingplan-feishu)、[阶跃](https://www.stepfun.com/chats/new)、[KIMI](https://www.kimi.com/bot)、[扣子](https://docs.coze.cn/tutorial/openclaw)、[MiniMax](https://agent.minimaxi.com/max-claw)、[智谱](https://docs.bigmodel.cn/cn/coding-plan/benefits/autoglm-openclaw)等平台也同样支持；各云端平台也均提供开发 Agent 辅助你调试，欢迎体验。
> 
> 本插件同步适用于Lark，以下「飞书」代指飞书 & Lark



你或许早就把小龙虾接到了飞书上，他能帮你写东西、查资料、出方案——但它也经常会说，"我没有飞书文档/消息/日历权限，请把内容发给我"，你不得不反复复制粘贴。

今天，飞书 OpenClaw 官方插件正式上线！

在获得你的授权后，OpenClaw 可以直接以**你的**身份看文档找资料、核对日历看档期、理解群聊上下文。

**你说一句话，它就能伸出“钳子”，直接在飞书里帮你把活儿干了。**

<grid>
<column width-ratio="0.333271">
![这是OpenClaw飞书官方插件的介绍图片，对应其可辅助用户处理消息的功能场景。图片展示了该插件“帮你拟好消息”的核心能力，上方的对话框说明具体场景：当用户在开会时，老板在群里询问进度，用户只需说一句话，插件就会读取群聊消息、理解上下文，按照用户与老板的关系拟好合适的回复。图片下方的聊天界面为功能演示实例，对应账号为“陈浩的龙虾”插件，示例问题是“看项目进度群我老板David说的话，帮我拟下回复”，界面下方显示了插件正在生成回复的加载状态。](https://feishu.cn/file/RsJCbOdwjo3f0IxL80dcJwAFnwd)
</column>
<column width-ratio="0.333364">
![图片展示了OpenClaw飞书官方插件的使用示例。上方文字说明其能帮你写好文档，称其读评论、定位原文、逐条修改，连编辑器都不用打开。下方是聊天界面，用户赵斯宁在群聊中提到对文档中某些内容看不懂，机器人回复按评论修改下文档，还展示了修改后的效果。该图片与上下文紧密相关，直观呈现了OpenClaw插件在文档修改方面的功能。](https://feishu.cn/file/GKuBbecSboRYx4xT04bcoLB0nSd)
</column>
<column width-ratio="0.333364">
![图片展示了OpenClaw飞书官方插件的使用示例。上方有“帮你做好待办！”的标题，下方对话框中显示“会议纪要里记了几条待办，你说一句：‘帮我先做了’”，并说明建文档、约会议、填表格等任务需拍板确认。下方是李天天的龙虾机器人回复，列出待办事项，包括写一篇关于明日科技项目进展情况的文档、预约一个本周的会议等。图片与上下文紧密相关，直观呈现了插件能根据指令自动处理待办事项的功能。](https://feishu.cn/file/O2YnbEHZOoDZwux9B4Ic80BunYE)
</column>
</grid>

更多玩法和灵感请查看 <cite doc-id="GGJPwJ2IfiTynVk2Vy4cZbRvn2f" file-type="wiki" title="OpenClaw x 飞书官方修炼指南" type="doc"></cite>。

## **支持的飞书能力**

| 业务类别 | 支持的能力 |
|-|-|
| 💬 消息 | 消息读取（群聊/单聊历史、话题回复）、消息发送（含发卡片）、消息回复、消息搜索、图片/文件下载 |
| 📄 文档 | 创建云文档、更新云文档、读取云文档内容 |
| 📊 多维表格 | 创建/管理多维表格、数据表、字段、记录（增删改查、批量操作、高级筛选）、视图 |
| 📊 电子表格 | 创建、编辑、查看电子表格 |
| 📅 日历日程 | 日历管理、日程管理（创建/查询/修改/删除/搜索）、参会人管理、忙闲查询 |
| ✅ 任务 | 任务管理（创建/查询/更新/完成）、清单管理、子任务、评论 |

<callout comment-refs="c128" emoji="💡">
以用户身份发消息需在飞书开放平台额外开通机器人 `im:message.send_as_user` 权限，部分企业（如字节）不支持此操作。
</callout>

此外，飞书官方插件还支持更好的互动体验，支持**流式输出卡片回复**（[需手动开启](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#ZI7XdyyOVoMVNUxNppicPQeHn6e)）、**识别合并转发消息**、**发表情**等，欢迎体验！

# ⚠️ 重要安全与风险提示（使用前必读）

### **🔴 核心风险**

该插件通过飞书接口连接了你的工作数据——消息、文档、日历、联系人，AI 能读到的东西理论上就有泄露的可能。虽然我们做了安全防护，但 AI 系统本身还不够成熟稳定，不能保证万无一失。

**🔴 强烈建议：**

作为机器人供多人使用或者通过公司飞书账号使用可能会导致数据安全和隐私风险，请注意使用时需要遵守企业内的数据安全和隐私要求，避免发生数据泄露、权限突破、侵犯隐私等后果。

**📌 其他操作风险**

- **AI 并不完美，可能存在“幻觉”：** 它有时会误解您的意图，或者生成看似合理但不准确的内容。
- **部分操作不可逆转：** 例如，AI 代发的飞书消息是以您的名义发出的，发出后即成事实。
- **应对建议：** 对于涉及发送、修改、写入等重要操作，**请务必做到“先预览，再确认”**，切勿让 AI 处于完全脱离人工干预的“全自动驾驶”状态。

### 💡OpenClaw 使用建议

<callout comment-refs="c223 c224" emoji="🦞">
**先拿个人账号安全地“玩”起来**，等后续安全隔离能力更成熟了，再考虑接入真实工作环境。
使用过程中遇到任何问题或体验不佳的地方，随时向我们反馈，我们正在持续快速迭代中！
</callout>

# 安装 OpenClaw 飞书插件

<callout emoji="🧭">
**前置依赖：** 需安装完成 OpenClaw ，版本要求如下：
- **Linux**/**MacOS：2026.2.26** 及以上
- **Windows：2026.3.2** 及以上 
飞书[现已支持一键部署 OpenClaw](http://openclaw.feishu.cn)，并自带本文介绍的飞书官方插件；[Coze 编程](https://docs.coze.cn/tutorial/openclaw)、[ArkClaw](https://www.volcengine.com/activity/codingplan-feishu) 等平台也同样支持一键部署OpenClaw 。
了解如何安装和更新OpenClaw，参见[文档](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#Znh2dk8FOomswFxzziXcjTvWn8d)
</callout>

1. 在命令行终端中，执行以下安装指令。

```Shell
    npx -y @larksuite/openclaw-lark install
```



<callout comment-refs="c287 c288 c289 c290 c291 c292 c293 c294" emoji="🏖️">
若执行命令行出错，可在命令行前增加 `sudo `重新执行。
</callout>

1. 执行过程中，可选择 **新建机器人** 或 **关联已有机器人**。

   ![这是OpenClaw飞书官方插件使用过程中的操作选择界面，显示已安装的插件为feishu-openclaw-plugin，提示需要重启网关加载插件。界面提供了两个操作选项，分别是新建机器人，以及使用OpenClaw已关联的机器人，该界面对应安装插件时的步骤选择环节，用户可通过方向键选定操作，符合文档中关于插件安装时选择新建或关联机器人的流程说明。](https://feishu.cn/file/XYzeb6lJYoiiTRxxL9ics43onOV)

   <callout comment-refs="c331 c332 c333 c334" emoji="🌟">
   选择关联已有机器人时，若提示无效的 App ID 或 App Secret，可手动输入正确的应用凭证信息。
   </callout>

   ![图片展示的是OpenClaw飞书插件安装后，选择关联已有机器人的操作界面。界面显示已安装插件“openclaw-lark”，并提示重启网关加载插件。接着询问用户操作，用户选择“Use an existing bot linked to OpenClaw”。随后输入App ID和App Secret，最后凭证校验成功。该图片与文档中“选择关联已有机器人时，若提示无效的App ID或App Secret，可手动输入正确的应用凭证信息”的内容相关，直观呈现了手动输入凭证的操作过程。](https://feishu.cn/file/OHZ8bmx3QoctS4xg9OXcL2qwnqc)
2. 若选择新建机器人，可通过飞书客户端扫描二维码，选择 **一键创建飞书机器人**。

   ![图片展示的是OpenClaw飞书插件安装后，选择新建机器人时的界面。界面中显示“Create a new bot（新建机器人）”的操作提示，下方有一个二维码，提示“Scan with Feishu to create your bot（请使用飞书扫码，创建机器人）”。下方还显示“Success! Bot created.（机器人创建成功！）”及OpenClaw相关信息。该图片与文档中“若选择新建机器人，可通过飞书客户端扫描二维码，选择一键创建飞书机器人”的内容对应，直观呈现了扫码创建机器人的操作场景。](https://feishu.cn/file/ZHwxbLYoNoPTFMxGHYoctKOvn19)

   <callout comment-refs="c360 c361 c350 c362" emoji="🧭">
   如果 Windows 设备中无法扫码成功，可能是因为终端的分辨率问题导致，建议更换终端使用 [Cmder](https://cmder.app/)。
   </callout>
3. 创建完成后，点击 **打开机器人**，在飞书中向机器人发送任意消息，即可开始对话。

<callout comment-refs="c378 c379 c380 c381 c382 c383 c384 c385" emoji="🐵">
- 若希望快速完成用户授权，便于后续 OpenClaw 通过你的身份完成消息、文档、多维表格、日历等任务，可以在飞书对话中发送 `/feishu auth`` `来完成批量授权。
- 为了让 OpenClaw 能学会这些新技能并正确使用，建议在飞书对话中发送 `学习一下我安装的新飞书插件，列出有哪些能力`。
</callout>

1. 验证是否安装成功：在飞书对话中发送 `/feishu start`。若返回了版本号信息，则代表安装成功。
2. 在OpenClaw 飞书插件中一键安装 [飞书CLI ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) 能力，安装后 飞书CLI 能力将自动绑定 OpenClaw 当前飞书机器人。

将以下内容 在飞书中 发送给OpenClaw 即可完成安装：

```Plain Text
请按照该文档帮我安装飞书cli：https://open.feishu.cn/document/mcp_open_tools/feishu-cli/set-up-lark-cli-for-ai-agents-in-openclaw_hermes.md
```

- 在飞书中体验更丰富全面的飞书操作能力，包括 消息与群组、云文档、云空间、电子表格、多维表格、日历、视频会议、妙记、邮箱、任务、知识库、通讯录、幻灯片、画板、OKR、审批、考勤
- 在安装时可以自由选择 OpenClaw 以什么方式与你协作：

  - 以机器人身份：AI将在飞书中以机器人的身份执行所有操作，适合作为团队助手,用于多人协作场景,如群聊问答、团队通知、公共文档维护。
  - 以你的身份：AI将在飞书中以你的名义执行所有操作，如读写文档、搜索消息、修改日程等，建议仅限个人使用。注意：该模式下请勿将此机器人分享给其他人使用,避免泄露你的飞书数据

> 温馨提示：如果你使用的是OpenClaw 中默认自带的飞书插件，也可以通过相同方式 使用   [飞书CLI ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) 能力



# 升级飞书插件版本

为提供更优质的用户体验，飞书团队正在快速优化迭代官方插件，详情参考 **飞书插件最新版本** [**更新日志**](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#TXlPdfLFKoC4F9xtdOYci3I6n5d)**。**



在终端中运行以下命令升级飞书官方插件到最新版本：

```Shell
npx -y @larksuite/openclaw-lark@2026.6.10 install --version 2026.6.10 --tools-version 1.0.47
```

<callout comment-refs="c418 c419 c420 c421 c422" emoji="🚅">
若执行该命令行出错，可在命令行前 增加 `sudo` 重新执行。
</callout>

![图片展示的是在终端中运行命令升级飞书官方插件后的反馈信息。内容显示已安装插件为openclaw-lark，提示重启网关以加载插件，随后进行诊断检查，结果显示所有检查通过，更新完成，新版本号为2026.3.12。该图片与文档中介绍升级飞书插件版本的内容相关，直观呈现了升级操作后的结果。](https://feishu.cn/file/AOXKbTrhyozrqHx2DUWcASnXnYe)

# 高级配置指令

## 切换到流式输出

- 切换到流式输出，可运行指令（如果是本地部署，需要去终端输入；如果是云端部署，去云端的对话框输入）：

```Shell
openclaw config set channels.feishu.streaming true
```

流式输出效果如图：

![这张图片展示的是OpenClaw飞书官方插件切换到流式输出后的效果，呈现了AI新闻相关的对话内容。页面左侧是用户发送的“哈喽，今天有什么AI新闻”的提问，插件在回复中整合了“近24h AI新闻速览”，内容涵盖算力与电力压力、AI智能体应用、AI与产业落地、资本市场动态等方面的多条资讯，还标注了每条资讯的发布时间，整体是插件流式输出功能的实际应用展示，体现了该插件能整合多类AI相关资讯并按时间更新的特点。](https://feishu.cn/file/QRIIbRk0Mo9ADBxIGIicstKQnah)

- 不用流式输出，可运行指令：

```Shell
openclaw config set channels.feishu.streaming false
```

- 流式输出卡片上支持显示更多内容

```Shell
openclaw config set channels.feishu.footer.elapsed true  # 开启耗时
openclaw config set channels.feishu.footer.status true  # 开启状态展示
```

## 设置多任务并行及独立上下文

机器人可在话题群/消息群话题模式中，针对每个话题拥有独立上下文以及多任务并行。

如需开启该能力，可运行指令：

```Shell
openclaw config set channels.feishu.threadSession true
```

如需关闭，可运行指令：

```Shell
openclaw config set channels.feishu.threadSession false
```

## 修改飞书机器人在群内的回复方式

目前插件支持的默认方式是机器人被拉进群后，只有 at 机器人时才可回复。 

**模式1：在群内机器人仅响应 应用所有者（主人）@机器人的消息，不响应其他人发给机器人的消息** （已作为3.17及以上版本安装时的默认策略，推荐配置）

**配置方法**

```JSON
{
  "channels": {
    "feishu": {
      "enabled": true,
      "appId": "cli_你的AppID",
      "appSecret": "你的AppSecret",
      "requireMention": true
      "groupPolicy": "allowlist",
      "groupAllowFrom": ["ou_XXXX"]，
      "groups": { "*": { enabled: true } }
    }
  }
}
```

将 groupPolicy 设置为 "allowlist"（白名单），并通过 groupAllowFrom 指定允许触发机器人的用户，配置你本人openid 信息。你可以直接咨询小龙虾你的openid。

再在 groups 中设置 requireMention: true，要求消息必须 @ 到机器人后才会回复。



**模式 2：只有 @机器人 才回复，可响应群内任何人发送的消息**

**配置方法**

```Shell
# 设置需要 @ 才回复
openclaw config set channels.feishu.requireMention true --json# 重启生效
sh /workspace/projects/scripts/restart.sh
```

**完整配置示例**

```JSON
{"channels": {"feishu": {"enabled": true,"appId": "cli_你的AppID","appSecret": "你的AppSecret","requireMention": true,"groupPolicy": "open"}}}
```

---



**模式 3：不用 @，所有消息都回复**

⚠️ 注意：这个模式在大群里容易刷屏，谨慎使用！

需要额外在开发者后台申请应用身份权限：获取群组中所有消息（敏感权限）`im:message.group_msg`。

**配置方法**

```Bash
# 设置不需要 @ 也回复
openclaw config set channels.feishu.requireMention false --json
# 重启生效
sh /workspace/projects/scripts/restart.sh
```

**完整配置示例**

```JSON
{"channels": {"feishu": {"enabled": true,"appId": "cli_你的AppID","appSecret": "你的AppSecret","requireMention": false,"groupPolicy": "open"}}}
```

---

**模式 4：只有指定群 @机器人才回复（高级）**

**效果**

- 大部分群：不用 @ 也能回复（或者完全不回复）
- 特定群：必须 @ 才回复
- 适合：不同群不同规则，比如工作群严格一点，闲聊群随意一点

**配置方法**

**第一步：获取群 ID**

可通过以下任意方式获取目标群 ID：

- 让机器人加入群后，发送任意消息，然后在日志里找群 ID，或让机器人回复群 ID。

![图片展示了飞书插件demo在群聊中回复的内容。上方显示“@飞书插件 demo 当前的群 ID 是多少（已编辑）”，下方回复“现在这个群聊的会话标识是： - chat_id（会话 ID / oc_xxx）: oc_5b8298c582237t...”。该图片与文档中“模式4：只有指定群@机器人才回复（高级）”配置方法相关，用于说明获取群ID的方式之一，即让机器人回复群ID，此图展示了机器人回复群ID的示例。](https://feishu.cn/file/OjkGbGdUbomG8vxX3c2cMzF5nph)

- 群成员可以通过点击右上角的群菜单选项进入群设置页面，查看群 ID。

  ![这张图片展示了飞书群聊界面的部分内容，右上角菜单中“设置”选项处于被选中状态，界面右下角清晰显示出该群的群ID为oc_eea5f860a50662。结合上下文可知，这是为了获取群ID以完成OpenClaw飞书官方插件模式4的配置，该模式需要绑定特定群的ID来实现“只有指定群@机器人才回复”的规则。](https://feishu.cn/file/UTvlbluDFovgKuxKJZccFqmZnwc)

**第二步：配置特定群规则**

```Bash
# 先设置默认所有群都不需要 @
openclaw config set channels.feishu.requireMention open --json# 然后给特定群设置需要 @（这里群ID只是示例，你要替换成真实的）
openclaw config set channels.feishu.groups.oc_xxxxxxxx.requireMention true --json# 重启生效
sh /workspace/projects/scripts/restart.sh
```

**完整配置示例**

```JSON
{"channels": {"feishu": {"enabled": true,"appId": "cli_你的AppID","appSecret": "你的AppSecret","requireMention": "open","groupPolicy": "open","groups": {"oc_532044075a61d112f04fa63109c75e9b": {"requireMention": true},"oc_另一个群ID": {"requireMention": true}}}}}
```

## 如何在飞书插件中配置 OpenClaw 关联多个飞书机器人，对应不同 Agent

详细操作参考：<cite doc-id="WNNXdhKxmo8KDJxMM9dc0GD5nFf" file-type="docx" title="如何在飞书插件中配置 OpenClaw 关联多个飞书机器人，对应不同Agent" type="doc"></cite>

**快捷方法**：

1. 创建新的飞书机器人，用于关联到新的账号上

    一键创建一个OpenClaw 机器人：[立即创建](https://open.feishu.cn/page/openclaw?form=multiAgent)

1. 告诉 AI 你想创建一个怎样的新 Agent，以及这个 Agent 关联的飞书账号是什么，并将操作指南发给 OpenClaw  请他自己完成对应配置：<cite doc-id="WNNXdhKxmo8KDJxMM9dc0GD5nFf" file-type="docx" title="如何在飞书插件中配置 OpenClaw 关联多个飞书机器人，对应不同Agent" type="doc"></cite>



## 如何集成飞书项目 Meego 读写能力

参考文档：[OpenClaw x 飞书项目集成实践](https://project.feishu.cn/b/helpcenter/1ykiuvvj/1n3ae9b4)



## 常用诊断命令与问题修复方法

可以在与 OpenClaw 的对话中发送以下命令：

- **/feishu start**：确认是否安装成功
- **/feishu doctor**：检查配置是否正常

![图片展示的是飞书插件诊断界面。上方显示“飞书插件诊断”，并提示工具配置检查异常，需按提示修改配置。下方列出“工具基础允许列表”等信息，如当前为“coding”等。中间有两条命令：1. openclaw config set tools.profile "full"；2. openclaw gateway restart。下方还显示“环境信息检查通过”“API连通性 - 连接成功”等信息，以及“应用身份权限检查通过”“用户身份权限检查未通过”等内容，还列出了部分权限名称及状态。该图片与文档中“常用诊断命令与问题修复方法”部分相关，用于指导用户诊断飞书插件问题。](https://feishu.cn/file/POQob95y2o7VdpxE36ZcSaLYnah)

- 工具配置检查异常，可根据提示的命令在命令行中运行并配置

```Plain Text
openclaw config set tools.profile "full"
openclaw gateway restart
```

- 应用身份权限未通过，可点击链接 申请权限并发布应用。
- 用户身份权限未通过

  - 如果涉及到应用权限未开通，则点击链接申请权限并发布
  - 如果是用户 暂无授权，则在对话框输入 /feishu auth 批量完成用户授权
- **/feishu auth**：批量完成用户授权



插件中也内置了常见问题的解决方案，遇到问题都可以先问问小龙虾。如果不行，则运行以下指令查看问题，并自主修复：

```TypeScript
npx @larksuite/openclaw-lark doctor
```

![图片展示的是在终端中执行`feishu-plugin-onboard doctor`指令后的结果。指令运行时显示“Running diagnostic checks...”，随后出现“\[FAIL\] Plugin not found in plugins.allow”错误提示，建议通过`--fix`选项自动添加插件。最后提示“Some checks failed. Use --fix to attempt automatic repair.”。该图片与文档中“遇到问题可运行以下指令查看问题，并自主修复”的内容相关，直观呈现了指令执行后的反馈信息。](https://feishu.cn/file/TLj1bks7xomh1cxnJD7cPFtYnrb)

运行 `fix` 尝试自动修复：

```TypeScript
npx @larksuite/openclaw-lark doctor --fix
```

![这是OpenClaw飞书插件使用中自动修复相关问题的终端操作界面截图，内容为使用`feishu-plugin-onboard doctor --fix`命令进行问题排查与修复的完整流程。界面显示，执行该命令后先检测到“Plugin not found in plugins.allow”的失败问题，接着系统自动尝试修复，将插件添加至允许列表，显示修复完成的反馈，提示需再次运行对应命令验证。用户按提示再次执行`feishu-plugin-onboard doctor`命令后，检测结果显示所有检查均已通过，完成问题的自动修复流程。](https://feishu.cn/file/Gc7pbXM3doWdH3xnR3OcX7oCnfg)

如果仍然无法修复，可在反馈群里反馈信息。

- 运行 `info` 查看版本信息，反馈问题时带上辅助排查。

```TypeScript
npx @larksuite/openclaw-lark info 
```

![图片展示了在终端运行`feishu-plugin-onboard info`指令后的输出结果。显示了`feishu-plugin-onboard`版本为1.0.6，`openclaw`版本为2026.2.26，`feishu-openclaw-plugin`版本为2026.2.28.11。该图片与文档中“运行`info`查看版本信息，反馈问题时带上辅助排查”的内容相关，用于说明查看插件版本信息的操作及结果。](https://feishu.cn/file/BPl6bd770oLpXxxvnfncQkqZnlb)

- `--all `查看详细配置信息

```TypeScript
npx @larksuite/openclaw-lark info --all
```

# 常见问题

## 升级到openclaw 4.27后，群消息不回复

Openclaw 4.27改了群的默认回复行为：https://github.com/openclaw/openclaw/blob/main/CHANGELOG.md?plain=1#L528，在openclaw.json中增加以下配置恢复（messages和channels同级）：

```Plain Text
{                                                                                                                     
    messages: {   
      groupChat: {
        visibleReplies: "automatic"
      }
    }
 }
```

##  Cannot find module '@larksuiteoapi/node-sdk'

预计openclaw 2026.4.22版本修复，在这之前可以按下面方式修复

- 进到openclaw目录

```Bash
cd "$(dirname "$(dirname "$(readlink -f "$(which openclaw)")")")"
```

- 手动安装缺失依赖

```Plain Text
npm install --no-save --legacy-peer-deps @larksuiteoapi/node-sdk
```

## 升级到openclaw 2026.3.28有问题

本插件2026.3.29版本兼容，如果升级不成功，可以指定升级脚本进行升级

```Plain Text
npx -y @larksuite/openclaw-lark update --tools-version 1.0.33
```

## 升级到openclaw 2026.3.22有问题

openclaw2026.3.22有breaking change，本插件2026.3.25版本兼容

**可直接运行npx @larksuite/openclaw-lark update进行升级；（推荐）**

```JavaScript
npx @larksuite/openclaw-lark update
```

如果没有成功升级到2026.3.25版本，可以指定升级脚本进行升级

```Plain Text
npx -y @larksuite/openclaw-lark update --tools-version 1.0.32
```

## 没有 OpenClaw 应该如何部署

- OpenClaw 是本次介绍的飞书插件的运行基础，请先选择符合自己需要的部署方案完成部署。
- 本地版建议使用 TRAE SOLO 等编程 Agent 辅助安装；

<grid><column width-ratio="0.554952"><ul><li comment-refs="c572">飞书<a href="http://openclaw.feishu.cn">现已支持一键部署 OpenClaw</a>，并自带本文介绍的飞书官方插件；<a href="https://docs.coze.cn/tutorial/openclaw">Coze 编程</a>、<a href="https://www.volcengine.com/activity/codingplan-feishu">ArkClaw</a> 等平台也同样支持；各云端平台也均提供开发 Agent 辅助你调试；欢迎体验；</li></ul><p></p></column><column width-ratio="0.445048"><figure view-type="Preview"><source name="飞书一键部署-PC.mp4" mime="video/mp4" origin-height="2156.000000" origin-width="3840.000000" size="18364143" token="DmbubjzQkoh2NrxYJrjc3WcQnlb"/></figure></column></grid>

## 在使用插件时出现权限不足，需要申请所需权限应该如何操作？

1. 在左侧导航栏选择 **权限管理**，点击 **批量导入/导出权限。**

   ![图片展示的是飞书开放平台的权限管理页面。页面左侧有导航栏，选中“权限管理”。右侧上方有“权限管理”标题，下方有“批量导入/导出权限”按钮被红色框突出显示。下方列出了部分权限名称、权限类型、权限状态及可访问的数据范围等信息，如“获取应用管理员ID”权限，其权限类型为应用身份，状态为已开通，可访问的数据范围为“与应用的可用范围一致”。该图片与上下文关于权限管理的操作说明相关，直观呈现了权限管理页面及操作按钮位置。](https://feishu.cn/file/P3DGbSYBToWrlQxSAAkcWLDdnvd)
2. 在 **导入** 页签中，复制下面权限替换原有示例，点击 **下一步，确认新增权限** 按钮。

```JSON
{
  "scopes": {
    "tenant": [
      "contact:contact.base:readonly",
      "docx:document:readonly",
      "im:chat:create",
      "im:chat:read",
      "im:chat:update",
      "im:message.group_at_msg:readonly",
      "im:message.p2p_msg:readonly",
      "im:message.pins:read",
      "im:message.pins:write_only",
      "im:message.reactions:read",
      "im:message.reactions:write_only",
      "im:message:readonly",
      "im:message:recall",
      "im:message:send_as_bot",
      "im:message:send_multi_users",
      "im:message:send_sys_msg",
      "im:message:update",
      "im:resource",
      "application:application:self_manage",
      "cardkit:card:write",
      "cardkit:card:read",
      "drive:drive.metadata:readonly",
      "docs:document.comment:create",
      "docs:document.comment:delete",
      "docs:document.comment:read",
      "docs:document.comment:update",
      "docs:document.comment:write_only",
      "docx:document:create",
      "docx:document:readonly",
      "docx:document:write_only",
      "docx:document.block:convert"
    ],
    "user": [
      "contact:user.employee_id:readonly",
      "offline_access","base:app:copy",
      "base:field:create",
      "base:field:delete",
      "base:field:read",
      "base:field:update",
      "base:record:create",
      "base:record:delete",
      "base:record:retrieve",
      "base:record:update",
      "base:table:create",
      "base:table:read",
      "base:table:update",
      "base:view:read",
      "base:view:write_only",
      "base:app:create",
      "base:app:update",
      "base:app:read",
      "sheets:spreadsheet.meta:read",
      "sheets:spreadsheet:read",
      "sheets:spreadsheet:create",
      "sheets:spreadsheet:write_only",
      "docs:document:export",
      "docs:document.media:upload",
      "board:whiteboard:node:create",
      "board:whiteboard:node:read",
      "calendar:calendar:read",
      "calendar:calendar.event:create",
      "calendar:calendar.event:read",
      "calendar:calendar.event:reply",
      "calendar:calendar.event:update",
      "calendar:calendar.free_busy:read",
      "contact:contact.base:readonly",
      "contact:user.base:readonly",
      "contact:user:search",
      "docs:document.comment:create",
      "docs:document.comment:read",
      "docs:document.comment:update",
      "docs:document.media:download",
      "docs:document:copy",
      "docx:document:create",
      "docx:document:readonly",
      "docx:document:write_only",
      "drive:drive.metadata:readonly",
      "drive:file:download",
      "drive:file:upload",
      "im:chat.members:read",
      "im:chat:read",
      "im:message",
      "im:message.group_msg:get_as_user",
      "im:message.p2p_msg:get_as_user",
      "im:message:readonly",
      "search:docs:read",
      "search:message",
      "space:document:move",
      "space:document:retrieve",
      "task:comment:read",
      "task:comment:write",
      "task:task:read",
      "task:task:write",
      "task:task:writeonly",
      "task:tasklist:read",
      "task:tasklist:write",
      "wiki:node:copy",
      "wiki:node:create",
      "wiki:node:move",
      "wiki:node:read",
      "wiki:node:retrieve",
      "wiki:space:read",
      "wiki:space:retrieve",
      "wiki:space:write_only",
      "contact:user.basic_profile:readonly"
    ]
  }
}
```

![这是OpenClaw飞书官方插件使用指南中，用于展示批量导入/导出权限操作的界面截图，属于解决权限不足需申请权限问题流程中的内容。界面包含“导入”“导出”两个选项卡，当前处于“导入”选项卡，下方提供了符合要求的权限数据格式参考，以JSON形式呈现了各类权限项。界面右下角有“取消”和“下一步，确认新增权限”按钮，结合上下文可知，该界面对应权限申请流程中确认权限导入环节的操作页面。](https://feishu.cn/file/Ih2JbQ00ooNWflxhFWWcMtG7n4f)

1. 确认导入权限无误后，点击 **申请开通** 按钮。

![图片展示的是OpenClaw飞书官方插件使用指南中“在使用插件时出现权限不足，需要申请所需权限应该如何操作？”问题下，确认导入权限的界面。界面上方有“应用身份权限”和“用户身份权限”两个选项卡，当前选中“应用身份权限”。下方列出20项新增权限，如管理应用自身资源、获取通讯录基本信息等。右下角有“取消”“上一步，导入权限”和“申请开通”按钮，其中“申请开通”按钮被蓝色框突出显示。该图与上下文紧密相关，直观呈现了申请权限的操作界面。](https://feishu.cn/file/NIiKbcSLxoGKDyxYtq8clkPGnwd)

1. “应用身份权限”可访问的数据范围的设置保持默认 "**与应用的可用范围一致**" ，点击 **确认** 完成操作。

![图片展示的是“应用身份权限”可访问的数据范围设置界面。左侧为“通讯录”选项，右侧显示关联应用身份权限，有“获取通讯录基本信息”选项。下方“权限可访问的数据范围”显示为“已开通”，并有“配置”按钮。界面底部有“展开”和“确认”按钮。该图片与文档中“在使用插件时出现权限不足，需要申请所需权限应该如何操作？”的上下文相关，用于说明权限申请后的数据范围设置情况。](https://feishu.cn/file/NZkpbeGMWoqjJGx0om0cvU3FnPf)



## 插件安装完毕运行后，报 cannot find module xxx

**原因**：系统没有安装插件的依赖（可能是安装被中断或权限问题）

**解决方法**：进入插件安装目录，运行 `npm install`。

![这张图片是OpenClaw插件运行失败的日志截图，显示了报错信息，对应插件安装完成后运行时出现“cannot find module xxx”的故障场景。截图中红色框选的区域标注出了相关的文件路径，明确了插件安装目录，红色箭头也指向该位置，结合文档上下文可知，这里的错误是因系统未安装插件依赖导致，对应的解决方法是进入该插件安装目录，运行`npm install`来解决问题，帮助用户定位故障位置。](https://feishu.cn/file/Oq4nb6KbtonQTXxnVsfcwGEwnIc)

## Coze上安装失败的处理方式

1. 依次在终端执行以下命令，如果未能正常运行，请等待飞书插件和 Coze 的后续更新。

```Shell
// 先执行
export NPM_CONFIG_REGISTRY=https://registry.npmmirror.com
```

```Shell
//👆若执行该行命令行出错，可在命令行前 增加 sudo 重新执行。
npx -y @larksuite/openclaw-lark install
```

1. 检查 OpenClaw 自带的 Feishu 插件的配置，参考下图。如果为`true`，需要改成 `false`。

![这是OpenClaw的配置页面截图，页面左侧导航栏中“配置”选项处于选中状态，对应“设置（Settings）”模块的内容。右侧区域的配置代码内容里，有红色箭头指向“plugins”分类下的“feishu”项，该项的“enabled”属性被设置为false，其余部分包含了插件安装相关的配置信息，该内容与升级到OpenClaw 3.2版本后无法正常调用工具的修复操作相关，对应文档中提及的修改配置以解决权限或工具调用问题的场景，提示需要调整对应“feishu”插件的权限设置。](https://feishu.cn/file/IXEMbpXFcorMVkxPd3KcsS9Rn6f)

## 升级到 OpenClaw 3.2 版本上无法正常调用工具

这个 OpenClaw 版本默认把新 agent 的工具权限关闭。修复方式为在 `openclaw.json` 找到并修改为下面这段内容：

```JSON
{
  "tools": {
    "profile": "full",
    "sessions": {
      "visibility": "all"
    }
  }
}
```

## 飞书官方插件与 OpenClaw 社区原有插件有何区别

飞书官方插件，能以用户身份读写消息、文档等，体验更丝滑；以下对比由 AI 整理，供参考。

![图片是一张对比表，对比了OpenClaw内嵌飞书与飞书官方插件在维护方、形态、上手难度、官方背书、Feishu原生对象能力、消息能力、流式回复、交互卡片、文档/表格/日历/任务、配置模型、群策略/权限策略、运维工具、诊断能力、扩展性、网络/企业环境适配、升级路径、风险、最适合谁等方面的内容。该表位于介绍飞书官方插件与OpenClaw社区原有插件区别的上下文部分，用于直观呈现两者差异。](https://feishu.cn/file/AgHUbJAhzou0rJxnsWkc1RkWn4b)

## 如何安装和更新OpenClaw？

1. 根据 [OpenClaw 官方指南](https://docs.openclaw.ai/start/getting-started)，执行以下安装命令，安装 OpenClaw：

   - **Linux**/**MacOS**： ：`curl -fsSL ``https://openclaw.ai/install.sh`` | bash`
   - **Windows**：`iwr -useb ``https://openclaw.ai/install.ps1`` | iex`  

   ![图片展示了在Linux或MacOS系统中安装OpenClaw插件的安装日志。命令为`curl -fsSL https://openclaw.ai/install.sh | bash`，检测到macos系统，安装方法为npm，显示了安装计划、环境准备、OpenClaw安装、最终设置等步骤，如Homebrew、Node.js、Git等已安装，OpenClaw v2026.3.8安装成功等。最后提示OpenClaw安装成功，可在线使用。该图与文档中如何安装和更新OpenClaw的内容相关，直观呈现了安装过程。](https://feishu.cn/file/AmkRbm53foPlgJxZdspcFVV9nxb)
2. 根据提示信息完成 OpenClaw 配置。以**方舟** **Coding Plan** 套餐进行对接为例，配置方式参考 [Coding Plan 接入 OpenClaw 官方文档](https://www.volcengine.com/docs/82379/2183190?lang=zh)。
3. 安装成功后，可以打开 OpenClaw Dashboard URL，正常显示管理后台则代表安装成功。

   ![这是OpenClaw Gateway Dashboard管理后台的概览页面，为OpenClaw飞书官方插件安装成功后可正常显示的界面。页面左侧为功能导航栏，当前选中“概览”模块；页面右侧的“网关访问”区域，标注了网关状态正常，其中WebSocket URL为ws://127.0.0.1，网关令牌为OPENCLAW_GATEWAY_TOKEN，语言设置为English；右侧“快照”区域显示最近握手状态为正常，运行时间为18分钟；页面底部还显示了近5分钟内的在线会话数、最近跟踪的会话数，以及定时任务处于已启用状态。该页面用于验证OpenClaw安装是否成功，对应指南中安装成功后需正常显示管理后台的要求。](https://feishu.cn/file/WjPMbO1lXopqIqxVZdtcCL8gnBd)



1. 在管理后台的聊天页面进行对话验证，若助手可以正常响应，则说明配置成功。

   ![这张图片是OpenClaw管理后台的聊天页面截图，属于该官方插件使用指南中安装配置相关的内容。页面左侧是功能导航栏，包含聊天、概览、频道等选项；右侧聊天区域中，显示了一条来自OpenClaw助手的提示消息，要求读取特定文件并回复“HEARTBEAT_OK”，消息还标注了当前时间；下方有用户发送的“你好”消息，以及输入框和“Send”发送按钮，整体对应指南中提到的配置成功后需进行的对话验证环节，用于确认助手可正常响应。](https://feishu.cn/file/UOGybJjnCoBihwx4nVrct8T0nHf)
2. 如何检测OpenClaw 的版本 并升级版本？

运行 `openclaw -v` 命令查看已安装的 OpenClaw 的版本

可执行 `npm install -g openclaw` 命令升级。

# 更新日志

## **2026.6.10**

- 优化bot相互对话的场景：在群里 @ 两个bot，它们能彼此 @ 对方、轮流接话，各自保持自己的身份和职责

## **2026.5.20**

> **兼容openclaw 5.7**

- 优化长连接稳定性

## **2026.5.13**

> **兼容openclaw 5.7**

- 注册飞书 SecretRef ，以便在运行时进行解析。
- 在为被路由代理（routed agents）解析 footer metrics session store 时，透传 agentId。
- 更新了视频会议受邀的合成提示词，要求代理（agent）立即使用可用工具加入会议。
- 移除了特定工具相关的表述，使提示词能兼容不同的会议工具实现。
- 针对服务触发的会议邀请事件，添加了明确的 “不要询问确认” 的引导

## **2026.5.12**

- 在bot at bot的能力基础上，支持了@mention的场景下AI 生成的 @用户 / @bot / @所有人 能正确渲染为飞书原生 mention 并触发对端提醒（之前是**灰色普通文本**不触发提醒）

## **2026.5.7**

- 兼容OpenClaw 2026.5.6

## **2026.4.10**

- 兼容OpenClaw 2026.4.27

## **2026.4.8**

- 兼容 OpenClaw 更新

## **2026.4.7**

- 支持在文档评论中 at openclaw 机器人，让openclaw 收到评论并进行评论回复。需要更新应用 到最新的权限、事件配置。具体配置方式可以重新执行安装命令，并重新扫码关联 已有应用，系统将自动添加权限、事件配置。

## **2026.4.1**

- 兼容 OpenClaw 2026.3.31

## **2026.3.31**

- 修复飞书卡片中的表格会多出一个空白行的问题
- OpenClaw 机器人显示“智能体”标签（在飞书客户端 V7.66 及以上版本将会展示）

## **2026.3.30**

- [减小卡片行间距，修复非默认账号 metrics，账号配置 deep-merge](https://github.com/larksuite/openclaw-lark/pull/317)
- [修复空卡片导致媒体发送失败](https://github.com/larksuite/openclaw-lark/pull/302)
- [修复定时任务配置加载校验](https://github.com/larksuite/openclaw-lark/pull/301)
- [修复安装过程过多OpenClaw 实例](https://github.com/larksuite/openclaw-lark/pull/340)

## **2026.3.29**

- 兼容openclaw 2026.3.28

使用下面命令安装

```Plain Text
npx -y @larksuite/openclaw-lark@2026.3.29 install --tools-version 1.0.33
```

## **2026.3.26**

- 修复了话题模式多话题并行时会话未隔离的问题
- 新增 AskUserQuestion 交互卡片工具
- 修复飞书卡片表格超限导致消息发送失败 Error 230099
- 过滤工具调用钩子，仅记录飞书自有工具
- 流式输出中保留 think 标签内容
- 减少飞书插件注册日志噪音
- 确保会话重置后收到欢迎消息

## **2026.3.25**

兼容 OpenClaw 2026.3.22 版本；由于 2026.3.22 版本存在不兼容更新，飞书插件的兼容策略如下：

- 当检测到当前 OpenClaw 版本 >= 2026.3.22 版本时，飞书插件将自动安装 **2026.3.25** 版本
- 当检测到当前 OpenClaw 版本 <  2026.3.22 版本时，飞书插件将自动安装 **2026.3.18** 版本**；**

如果你尚未安装飞书插件，可执行 [安装命令](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh?contentTheme=DARK&last_doc_message_id=7620655426846002396&preview_comment_id=7620655507530910652&sourceType=feed&theme=light#SoWpdMkx1oxMzlxcY8qcFlC3nwb)，如果你已使用插件，则执行 [更新指令](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#KqvSdNrxtoMSKkxMSeCcXnvTnjh)。



## **2026.3.17**

- **提升安全策略：**安装插件后的默认策略调整，“从群内可响应任何人@机器人的消息”调整为“在群内仅响应应用创建人@机器人的消息”。如果你已在使用飞书插件，更新插件时不会自动修改该配置，可参考 [配置方式](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh?contentTheme=DARK&last_doc_message_id=7618794739840273606&preview_comment_id=7618794861008833714&sourceType=feed&theme=light#share-JgVSd7QZkoMySAxvUTicH5wenqd) 手动完成配置。
- **问题修复：**部分场景下通过用户ID 无法获取用户名称的问题已修复，可更加顺畅获取消息发送人、文档评论人等信息

## **2026.3.15**

-  OpenClaw 插件可支持 Lark 海外品牌使用，参考 [操作手册](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#M0usd9GLwoiBxtx1UyjcpeMhnRe)

## **2026.3.12**

- 修复插件升级后 warning 提示"plugin id mismatch" 错误，可以参考这里的更新指令快速升级到最新版，参考 [更新指令](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#KqvSdNrxtoMSKkxMSeCcXnvTnjh)。

## **2026.3.10**

- **安装流程简化：**只需执行一行命令，3分钟内即可完成安装飞书插件及飞书机器人的配置，参考 [操作手册](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#M0usd9GLwoiBxtx1UyjcpeMhnRe)。
- **支持多账号能力：**在飞书中为多个 Agent 配置独立的飞书应用机器人，参考 [配置方式](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#Xih9dj64BoimgtxiHN7cngLnnQh)。
- **飞书插件已正式开源：**欢迎访问 [Github](https://github.com/larksuite/openclaw-lark) 并关注我们！欢迎大家一起交流\~

如果你已经用上了我们的插件，建议更新到我们的新插件，可以参考这里的更新指令快速升级到最新版，参考 [更新指令](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#KqvSdNrxtoMSKkxMSeCcXnvTnjh)。

## **2026.3.8**

- **支持电子表格的读写**：小龙虾现在可以帮你看表格数据、追加内容啦！使用前记得在开发者后台导入电子表格相关权限，参考 [权限配置](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#JkV7dSXRSortxbxbaeEcl6SDn8c)。
- **支持在云文档中添加文件和图片**：小龙虾写文档时可以插入图片、文件附件了，让文档内容更丰富。
- **AI 可感知表情反馈**：小龙虾现在能"看懂"你的表情了！收到你的 👍、❤️ 等表情后，可以据此调整回复逻辑，比如通过 👍 确认操作执行。

## **2026.3.7-beta.1** 

- 修复 Windows 使用反复授权问题。

## **2026.3.6**

- **安装支持 Windows 环境**：已支持 Windows 系统安装插件。
- **话题群和话题模式群能力升级：**可通过命令一键开启在话题群、话题模式群中让每个独立话题中拥有独立上下文和并行执行任务，让小龙虾同时干多件事，参考 [配置方式](https://bytedance.larkoffice.com/docx/MFK7dDFLFoVlOGxWCv5cTXKmnMh#CbJKd6GmhoUAS0xUbZWcyAd1nDg)。
- **问题修复：**修复知识库文档无法读取评论的问题，修复 `/feishu doctor` 指令中版本号错误问题。

# 用户内测体验互助群

> 欢迎群内大家彼此帮助回复问题，老玩家带带新玩家，一起探索龙虾新玩法提升工作效率

<synced_reference comment-refs="c734" src-block-id="Fg1gdH5fesU9d0bICVfck7hQnkh" src-token="XaTOdwWqAoObAqxIWd5c3Um3nPe"></synced_reference>



群已满

<chat_card name="OpenClaw 飞书插件体验互助10群" chat-id="oc_36a3baed4055d9f42062dba86e7a7756" comment-refs="c735 c736"></chat_card>



# ⛲️ 许愿池

想让插件支持什么新能力？在这里许个愿吧。你可以提交自己的需求，也可以给别人的愿望 +1。我们会定期查看并回复，票数高的需求会优先安排。你的每一票都在影响我们的迭代计划～💗

- 点击填写许愿 👉  [许愿提交](https://bytedance.larkoffice.com/share/base/form/shrcnD1BQ6OAX3avYZ8SfozpPnd?prefill_%E6%A8%A1%E5%9D%97=OpenClaw+%E6%8F%92%E4%BB%B6) 
- 点击 +1，为你感同身受的许愿投票 （当前需要点击进入[原表格](https://bytedance.larkoffice.com/base/Ebxvb6usfakMENs2GHIcL5Ern2f?table=tbl3HAHYqRF0ZSM6&view=vewXj9rPPG)投票，优化ing）

<base_refer comment-refs="c739" table-id="tbl3HAHYqRF0ZSM6" token="Ebxvb6usfakMENs2GHIcL5Ern2f" view-id="vewXj9rPPG"></base_refer>
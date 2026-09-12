# 最新爆火的开源 Agent — Hermes 现已官方支持连接飞书

<grid><column width-ratio="0.500000"><img name="img_v3_0210o_1a984325-bf02-480d-b2c0-f8f3fa2d9b1g.jpg" alt="图片展示了Hermes Agent官方原生支持连接飞书的信息。上方有飞书和Hermes Agent的标志，中间大标题为“Hermes Agent现已官方原生支持连接飞书”，下方文字说明一键部署，快速连接海量飞书上下文和工具。图片还呈现了GitHub上Hermes Agent v0.9.0版本的页面截图，显示了相关代码、issues、pull requests等信息，底部有“DM mention threads + group chat events for Feishu (#7423)”和“Feishu QR-based bot onboarding (#8570)”两项内容。最下方提示访问open.feishu.cn/hermes了解详情。" mime="image/jpeg" scale="1.000000" src="TmvQb2h1voBrWqxiXwzci8ENnLh"/></column><column width-ratio="0.500000"><blockquote><p>Hermes 现已官方支持连接飞书、安装飞书 CLI，访问项目 <a href="https://github.com/nousresearch/hermes-agent">github</a> 或 <a href="https://hermes-agent.nousresearch.com/">官网</a> 安装即可立即体验；</p><p>了解飞书CLI请访问：<cite doc-id="WnHkdJQM6oGpQFxm9i7ckVdenSh" file-type="docx" title="飞书 CLI 能力介绍与最佳实践" type="doc"></cite></p><p>本文由泽腾与 AI 共创，如有问题欢迎评论</p></blockquote><callout emoji="💡"><p>2026 年 2 月，Nous Research 发布了 Hermes Agent——一个会自我学习的开源 AI Agent，上线不到两个月 GitHub 就突破了 24,000 星标。而现在，Hermes 已正式将飞书纳入官方支持的工具列表，你可以轻松在Hermes 连接飞书、安装飞书 CLI。<b>你可以让一个持续进化的 AI Agent，直接在飞书里帮你干活了。</b></p></callout><p></p></column></grid>

## Hermes 是什么？

**一句话：Hermes 是一个运行在你自己服务器上、用得越久越聪明的开源 AI Agent。**

Hermes 由 AI 研究实验室 Nous Research 开发（获 Paradigm 领投 6500 万美元融资），基于自研 Hermes 模型家族构建。与一般 Agent 不同，它有一套闭环学习机制——能记住跨会话的上下文，自动把完成过的复杂任务沉淀为可复用的"技能文档"，并在使用中持续自我改进。它支持 400+ 模型（含本地部署），通过 Telegram、Discord、Slack、飞书等 8 个平台与你交互，可以 7×24 小时驻留在服务器上自主运行。

## 接入飞书 CLI 后，Hermes 获得了什么？

AI 模型都很聪明，但聪明不等于有用。一个 Agent 如果不知道你今天开了什么会、跟谁聊了什么、手上有哪些待办，它就只能给你通用的回答。而且就算它知道了，如果不能直接操作飞书，它还是只能说"你应该去建个文档"，而不是替你建。

**飞书 CLI 同时解决了这两个问题：给 Agent context，也给它"手"。**

<callout emoji="💡">
### Context：海量工作上下文
</callout>

接入飞书 CLI 后，Hermes 可以读取你在飞书上沉淀的所有工作信息——即时消息、云文档、电子表格、多维表格、日历、妙记、邮箱、知识库、任务、通讯录。它不再是一个"什么都不知道的聪明人"，而是一个了解你工作全貌的助手。

<callout emoji="💡">
### 手：直接操作飞书
</callout>

Hermes 不只是能"看"，还能"动手"——创建文档、发送消息、建多维表格、约会议、搜索知识库、处理邮件。**不是生成一段文字让你复制粘贴，而是直接在飞书里把事情办了。**

此外，飞书 CLI 还有以下特点：

**为 AI 而设计**

飞书 CLI 不是把现有 API 简单包装成命令行。它是为 AI Agent 的使用方式专门设计的：出错时告诉 AI 怎么修（不只是"错了"），缺权限时自动引导补授权，命令设计上优化了 token 消耗。AI 用它的成功率远高于直接调 API。

**全面开源，自由集成**

无需登记，无需审核。飞书 CLI 现已面向所有用户开源（[GitHub](https://github.com/larksuite/cli)）。不管你用 Hermes、Claude Code、Codex 还是其他 Agent，只要能跑命令行，就能通过 CLI 操作飞书。

## Hermes × 飞书 CLI：5 个实战场景

以下是 Hermes 接入飞书 CLI 后的一些典型使用场景。

> 更多场景详见 [飞书 CLI 能力介绍与最佳实践](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh)

### 场景一：一句话整理本周所有会议纪要

**痛点**：每周花 1-2 小时手动整理散落在妙记里的各种会议记录，格式不统一，关键决策埋在冗长的逐字稿里。

**现在**：告诉 Hermes "整理我本周所有会议的纪要"，它自动拉取本周的妙记，提取待办、决策和关键讨论，按统一格式写入飞书文档或多维表格，还能把更新日志推送到群聊。

**Hermes 加持**：Hermes 处理过几次你的会议后，会自动沉淀一个"会议纪要整理"技能文档——记住你偏好的格式、关注的信息类型、推送的目标群。第三次再执行时，速度更快、结果更准，不需要你重复描述需求。

```Plain Text
读一下我本周的妙记，把里面的待办和关键决策提取出来，写进一篇飞书文档。做之前给我看一下你的计划。
```

### 场景二：AI 当你的隐形审稿人

**痛点**：改别人的方案或文档要反复沟通，效率低。自己写的东西也很难发现逻辑漏洞。

**现在**：让 Hermes 阅读一篇飞书文档，以评论的形式指出逻辑漏洞、数据缺失、表述不清的地方，和你在评论区讨论——就像有一个随时在线的资深同事帮你 review。评论设为"仅自己可见"，确认后再以你的身份公开发出。

**反过来也行**：你写好初稿让 Hermes 润色，或者 Hermes 先起草、你在文档评论里提意见，它读取评论直接改正文，全程不离开飞书。

```Plain Text
{{文档链接}} 阅读一下这篇文档，看下逻辑是否清晰。不要直接改文档，只把你觉得有优化空间的位置划词评论出来。

人工检查、修改相关评论后：

根据文档上的评论帮我修改
```

### 场景三：妙记视频→自动剪辑精华片段

**痛点**：会议录制躺在妙记里没人看。想做内容沉淀或团队分享，但手动从一小时视频里找精华、剪辑、配字幕，工程量巨大。

**现在**：Hermes 通过飞书 CLI 下载妙记的视频源文件和逐字稿，自动识别高光片段（关键决策、重要演示、精彩讨论），调用 FFmpeg 剪辑成短视频，配上自动生成的字幕。会议录制从"存档"变成"可消费的内容"。

**Hermes 加持**：Hermes 会学习你对"精华片段"的判断标准。最初它靠通用规则，但当你修正过几次（"这段不重要"、"这段要保留"），它的选择会越来越符合你的口味。这个工作流本身也可以用来产出团队周报视频、产品 demo 等内容。

```Plain Text
下载这个妙记的视频，帮我识别里面最重要的3-5个片段，剪成短视频。做之前先给我飞书文档逐字稿，我来确认片段选择。
```

### 场景四：Markdown 一键变精美飞书文档 + 自动画架构图

**痛点**：在 AI 工具里用 Markdown 写完技术方案，想发给同事看，还得手动搬格式到飞书文档。更头疼的是画架构图——要切到画图工具，手动画完再贴回来。

**现在**：直接告诉 Hermes "把这个 Markdown 创建成飞书文档"，高亮块、表格、代码块全部自动保留。如果文档里提到了架构设计，Hermes 还能理解内容后自动生成 Mermaid 架构图、流程图、时序图，直接插入文档。

**反过来也行**：从飞书文档导出成 Markdown，方便在 GitHub 或其他平台发布。

```Plain Text
把这篇 Markdown 内容创建成飞书文档，排版要好看，里面提到的架构设计帮我画一张架构图的画板插进去。
```



## Hermes 相比其他 Agent 有什么不同？持久记忆与自我进化

大多数 Agent 的"记忆"本质上只是存了你的聊天记录。Hermes 走得更远：它用 FTS5 全文搜索 + LLM 摘要实现跨会话的真实召回，能搜索数周前的对话细节。更关键的是，完成复杂任务后，它会自动将经验沉淀为"技能文档"——下次遇到类似任务直接加载，且技能在使用中会持续自我改进。

社区反馈显示，有用户在 Hermes 创建了 3 个技能文档后，重复性研究任务速度提升了约 40%。

**Hermes、OpenClaw等Agent怎么选？** Hermes 适合重视长期记忆和自我进化、希望 Agent 越用越好的用户；OpenClaw 适合需要最大社区生态和成熟多 Agent 编排的场景；Claude Cowork 适合想要零配置、开箱即用桌面体验的用户。它们之间不是替代关系——不少用户同时使用 Hermes 和 OpenClaw，各取所长。



---

## 如何安装 Hermes 和飞书 CLI

### 第一步：安装 Hermes Agent，一行命令搞定

**一行命令搞定**

安装版本 >= v0.9.0

```Bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
```



### 第二步：初始化 Hermes，一键连接飞书

在「终端」中运行以下命令，Hermes 向导会引导你连接 LLM 提供商、连接飞书等；跟着指示操作即可

```Bash
hermes setup
```

<grid>
<column width-ratio="0.333333">
![图片展示了Hermes Agent安装向导界面。界面中显示“Hermes Agent Setup Wizard”标题，提示用户配置Hermes Agent安装，按Ctrl+C可退出。下方有“OpenClaw Installation Detected”信息，表明检测到OpenClaw安装，Hermes可预览更改前将导入的内容。底部有“Would you like to see what can be imported? \[Y/n\]:”的提示，当前输入为“n”。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，是初始化Hermes时向导引导用户配置安装步骤的界面展示。](https://feishu.cn/file/OhVkbnKV4ouCHxx2XP3cbPL6nAb)
是否导入OpenClaw，可选否（N）
</column>
<column width-ratio="0.333333">
![图片展示的是Hermes向 0.9.0版本安装后的初始化界面。界面上方显示“bytedance - python3 ~/.local/bin/hermes setup - 80x24”。下方提示“你想要如何设置Hermes？”，并给出两个选项：(e) Quick setup - provider, model & messaging (recommended) 和 (o) Full setup - configure everything。当前选中的是(e) Quick setup选项。该图片与](https://feishu.cn/file/JtI5bA6Qiobporx2Royceladnzg)
选择快速安装、选择你的模型、配置模型 API
</column>
<column width-ratio="0.333333">
![图片展示的是Hermes向导在终端中引导用户连接IM工具的界面。界面上方提示“Connect a messaging platform? (Telegram, Discord, etc.)”，下方有上下箭头导航、Enter/Space选择、Esc取消等操作说明。画面中突出显示了两个选项，分别是“Set up messaging now (recommended)”（立即设置IM，推荐）和“Skip - set up later with 'hermes setup gateway'”（跳过 - 后续通过'hermes setup gateway'设置）。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，是选择配置IM工具步骤的展示。](https://feishu.cn/file/KUjDbtLmboyk5WxaG1fc3yQqnNc)
选择配置 IM 工具
</column>
</grid>

<grid>
<column width-ratio="0.333333">
![图片展示的是Hermes向导在配置IM工具时的界面。界面上方显示“Select platforms to configure:”，下方列出多种IM工具选项，如Telegram、Discord等。其中“Feishu / Lark (configured)”以绿色高亮显示，表明已配置。该图片与上下文紧密相关，上下文提到在选择配置IM工具时，需按空格选中飞书后按Enter下一步，此图直观呈现了配置IM工具时的界面及已配置的飞书状态，帮助用户理解操作流程。](https://feishu.cn/file/G73jbWMigo4TLtxDl1qcEeNtntf)
选择飞书，按空格选中飞书后，按Enter下一步
</column>
<column width-ratio="0.333333">
![图片展示的是Hermes向导引导连接飞飞书时的界面。界面上方显示“bytedance - python3 ~/.local/bin/hermes setup - 80x24”。中间有提示信息，询问用户如何设置飞书/乐享，给出两个选项：(e) 通过扫描二维码自动创建新机器人（推荐）；(c) 手动输入现有App ID和App Secret。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，是选择飞书扫码连接飞书步骤的界面呈现。](https://feishu.cn/file/MxolbmGgYoSwdyxBDRjcLy09nCc)
选择飞书扫码连接飞书
</column>
<column width-ratio="0.333333">
![图片展示的是Hermes向导引导连接飞书时的终端界面。在选择配置IM工具步骤中，选择飞书后按空格选中飞书并按Enter下一步，接着选择飞书扫码连接飞书。界面显示飞书/ Lark已配置，询问是否重新配置，选择“y”后显示连接飞书完成。下方提示在手机飞书/ Lark中打开此网址：https://open.feishu.cn/page/openclaw?user_code=...&from=hermes&tp=hermes，还提示可使用pip install qrcode安装二维码插件以显示二维码。](https://feishu.cn/file/Ma7dbSnQGoPfJjx4Q1mcBFQenAe)
链接复制到浏览器或扫码（如有）配置飞书
</column>
</grid>

<grid>
<column width-ratio="0.276625">
![图片展示的是Hermes Agent创建飞书机器人界面。上方标题为“创建 Hermes Agent 飞书机器人”。界面中有头像选择区域，显示多个头像选项，当前选中一个黄色头像。下方有名称输入框，已输入“Larkin的智能助手”。底部有“创建”和“选择已有机器人”两个按钮。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，是选择新建飞书机器人或使用已有机器人操作的界面展示，用户可根据需求选择相应操作。](https://feishu.cn/file/KypJby7jvo6oJuxCDUhcxdDSndd)
选择新建飞书机器人或使用已有机器人
</column>
<column width-ratio="0.389343">
![图片展示的是Hermes Agent配置成功的界面。上方有图标，下方文字显示“创建成功，Hermes Agent正在配置中，请等待Hermes Agent网关重启完成后，打开机器人开启对话”，并有一个蓝色的“打开机器人”按钮。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，是初始化完成后，Hermes Agent配置成功的提示画面，提示用户等待网关重启并打开机器人开启对话。](https://feishu.cn/file/KnQhbPtKUof889xg3gFcRmzhnNb)
看到这个提示，回到终端
</column>
<column width-ratio="0.334032">
![图片展示的是Hermes向导在终端中引导用户连接飞书时，关于消息配对授权的选择界面。界面上方显示“Hermes向导”标题，下方提示“如何应答直接消息的授权？”，有“使用配对确认（推荐）”“允许所有直接消息”“仅允许列出的用户ID”三个选项，其中“使用配对确认（推荐）”被选中。该图片与文档中“设置消息如何配对，默认为私信配对”的上下文对应，是用户在初始化Hermes、连接飞书时配置消息配对方式的步骤之一。](https://feishu.cn/file/C6bFbwF81od7GhxBKw2cz5oJnmS)
设置消息如何配对，默认为私信配对
</column>
</grid>

<grid>
<column width-ratio="0.333333">
![图片展示的是Hermes向导在设置群聊响应方式时的界面。界面上方显示“群聊应如何处理？”，下方有“仅在群聊中@提及时响应（推荐）”和“禁用群聊”两个选项，当前选中的是“仅在群聊中@提及时响应”。该图片与文档中“设置群里如何响应，默认为选择需@bot”的内容对应，直观呈现了设置群聊响应方式的操作界面及推荐选项。](https://feishu.cn/file/LksTbeoQioGZLNxEpBFcGiTcnRh)
设置群里如何响应，默认为选择需@bot
</column>
<column width-ratio="0.333333">
![图片展示的是在终端中设置Hermes连接飞书时的界面。界面显示询问是否重新配置飞书，选择跳过保持当前设置。连接飞书已完成，下方给出了一个需在手机飞书中打开的URL链接，用于配置飞书。还提示可安装qrcode以便下次显示可扫描二维码。此外，显示已启用私信配对，未知用户可请求访问，可使用‘hermes pairing approve’批准，也已启用群聊（需@机器人）。该图片对应文档中“选择飞书扫码连接飞书”及后续步骤的内容，是操作过程中的一个状态展示。](https://feishu.cn/file/WJ8Qb5T3sorGPHx40W8cF2Isn1s)
此处设置定时任务推送群，可先跳过
</column>
<column width-ratio="0.333333">
![图片展示的是Hermes初始化并连接飞书后的终端界面。界面显示“DM pairing enabled”等配置信息，其中“Feishu / Lark configured!”以绿色突出显示，表明飞书配置成功。下方提示“Messaging platforms configured!”，并询问是否重启网关以应用更改，有“Y/n”选项。该图片与文档中“第二步：初始化Hermes，一键连接飞书”内容相关，直观呈现了Hermes完成飞书配置后的终端反馈情况。](https://feishu.cn/file/ACRxb0b0PoEQcqxE2d1cH4IJnvf)
![图片展示的是H addCriterion](https://feishu.cn/file/H57XbVMYTowxFOxtT1zcf9Jynlb)
重启网关、启动Hermes对话
</column>
</grid>

<grid>
<column width-ratio="0.471104">
![图片展示了在飞书中与Hermes智能体的对话界面。上方显示时间为12:14，智能体头像为一位戴着黄色帽子的女性形象。对话中，用户“hi”后，智能体回复“嗨~ 我还不认识你呢！这是您的配对码：R7C9LMER，请机器人所有者运行：hermes pairing approve feishu R7...”，并给出了配对码及指令。该图片与文档中“在飞书中搜索你的Bot和他打招呼，获得配对码，在终端对话完成配对”的内容相关，直观呈现了配对码获取的对话场景。](https://feishu.cn/file/O9d1bjSRroojWrxQTjycFFRonog)
在飞书中搜索你的Bot和他打招呼，获得配对码
</column>
<column width-ratio="0.528896">
![图片展示的是在终端完成Hermes与飞书配对后的界面。屏幕背景为黑色，文字为淡黄色等。界面顶部显示路径信息，中间有欢迎语，提示可输入消息或命令。下方有执行的命令“hermes pairing approve feishu”，显示初始化代理等进程。关键部分是底部提示“ Hermes User 'ou_844924' on Feishu can now use the bot...”，表明飞书用户已可使用该机器人，与上文在终端对话完成配对的内容相呼应，展示了配对成功后的状态。](https://feishu.cn/file/RpBQbqaMSohA4SxfHSdc9V4Inwb)
在终端对话完成配对
</column>
</grid>

### 第三步：安装飞书 CLI （一键安装，自动绑定 Hermes 当前机器人）

支持在 Hermes 中一键安装 [飞书CLI ](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh?preview_comment_id=7631945086829382599) 能力，安装后 飞书CLI 能力将自动绑定 Hermes 当前飞书机器人。

- 在飞书中体验更丰富全面的飞书操作能力，包括 消息与群组、云文档、云空间、电子表格、多维表格、日历、视频会议、妙记、邮箱、任务、知识库、通讯录、幻灯片、画板、OKR、审批、考勤
- 在安装时可以自由选择 Hermes 以什么方式与你协作：

  - 以机器人身份：AI将在飞书中以机器人的身份执行所有操作，适合作为团队助手,用于多人协作场景,如群聊问答、团队通知、公共文档维护。
  - 以你的身份：AI将在飞书中以你的名义执行所有操作，如读写文档、搜索消息、修改日程等，建议仅限个人使用。注意：该模式下请勿将此机器人分享给其他人使用,避免泄露你的飞书数据

**安装方式：**

给 **Hermes 飞书机器人** 发送以下内容即可：

```Plain Text
请按照该文档帮我安装飞书cli：https://open.feishu.cn/document/mcp_open_tools/feishu-cli/set-up-lark-cli-for-ai-agents-in-openclaw_hermes.md
```





现在，Hermes 就能直接调用飞书 CLI 来操作你的飞书——创建文档、读写表格、管理日程、发送消息、操作知识库……**AI 再聪明，没有手也干不了活。飞书 CLI 就是给 AI 的那双手。**

![图片展示了Hermes飞书机器人的对话界面。用户询问“你能用飞书技能做什么？”，Hermes回复已安装23个飞书技能，可直接通过lark-cli操作，包括IM、日历、多维表格等技能，列举了如搜索群聊成员、查看日程、管理共享日历等具体操作。该图片与上下文紧密相关，直观呈现了Hermes飞书机器人安装飞书CLI后的功能，强调其能通过lark-cli在飞书里操作，与上下文介绍的Hermes+飞书CLI功能相呼应。](https://feishu.cn/file/CtYrbckTwobUuBx9ck3cB1ykncf)

**Hermes + 飞书 CLI，让 AI 不只是陪你聊天，而是真正替你在飞书里打工，并和你一起持续进化！**

## **入群参与讨论、订阅后续更新**

<chat_card name="Hermes Agent 飞书体验互助1群" chat-id="oc_89bcd79c8462f507c016d807c2cae675"></chat_card>

<chat_card name="【字节内】Hermes Agent 飞书体验互助群" chat-id="oc_7bb271169d2b11db55f3e3e7574b0e74"></chat_card>



## FAQ

1. Hermes Agent 接入飞书，应该用 Hermes 官方飞书插件，还是飞书 CLI？

**两者不是二选一，而是互补的**

|  | 用途 |
|-|-|
| **Hermes 官方飞书插件** | 让 Hermes Agent 能在飞书消息中与用户对话、接收指令、回复消息 |
| **飞书 CLI** | 给 Hermes Agent 扩展操作飞书资源的能力（读写云文档、多维表格、电子表格、日历日程、会议、任务、邮箱等） |
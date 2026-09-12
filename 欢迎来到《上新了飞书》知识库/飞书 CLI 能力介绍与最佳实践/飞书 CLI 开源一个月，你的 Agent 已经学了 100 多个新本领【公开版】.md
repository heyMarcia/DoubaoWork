<title>飞书 CLI 开源一个月，你的 Agent 已经学了 100 多个新本领【公开版】</title>

<grid><column width-ratio="0.500000"><callout emoji="📌"><p><b>飞书 CLI</b> 是飞书官方开源的命令行工具，把飞书 2500+ 开放 API 封装成对 AI 友好的命令，让 Claude Code、Cursor、OpenClaw 等任何 Agent 一行命令接入飞书全套办公能力。</p><p>本文列出的能力均已上线飞书 CLI，为你的 Agent 安装最新 CLI 版本即可体验！</p><p><a href="https://www.feishu.cn/feishu-cli"><b>查看官网</b></a> ｜ <a href="https://github.com/larksuite/cli"><b>查看 Github</b></a><b> </b>｜ <a href="https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh"><b>使用指南</b></a></p></callout><blockquote><p>实际使用效果可能受模型能力、Agent架构、你的上下文等多种因素影响，欢迎<a href="https://go.larkoffice.com/join-chat/9edv1804-bd9b-41a1-a754-ffad3c1d8580">入群交流</a></p></blockquote><p></p></column><column width-ratio="0.500000"><p>视频了解本次更新⬇️</p><figure view-type="Preview"><source name="finalcomp-带封面.mp4" mime="video/mp4" origin-height="1920.000000" origin-width="1080.000000" size="44108916" token="CvgVbPym6olS8ExIQ0BcNWJbn0f"/></figure></column></grid>



# CLI 是什么？为啥我需要 CLI？

你可能觉得 CLI（命令行工具）是程序员的东西，跟自己没关系。换个方式理解：

**你跟 AI 的对话，其实不是两个人的私聊，而是一个三人群聊。**

群里有三个人：你、AI、你的电脑（或者说飞书）。

- 你发消息 = 你在跟 AI 说话
- AI 执行命令 = AI 在跟飞书说话
- 飞书返回结果 = 飞书在回复你们俩

**以前的问题是：飞书没有加入这个群聊。** AI 再聪明，它跟飞书之间没有沟通渠道，所以只能给你建议，不能帮你干活。

**飞书 CLI 就是把飞书拉进了这个群聊。** 装上之后，AI 终于能直接跟飞书对话了：帮你查日历、发消息、写文档、建表格。

所以 CLI 跟你的关系是：**你完全不需要学它，甚至不需要知道它存在。** 你只管用自然语言跟 AI 说话，AI 会自己用 CLI 去操作飞书。你只需要安装一次，之后就忘了它吧。



# 过去一个月，你的 Agent 结合飞书 CLI 又有了哪些新玩法？



飞书 CLI 开源一个月

已有 100 多项新能力，全部上线可用

以下这些能力，你只需把你的飞书 CLI 升级到最新版即可体验！



## 一、多 Agent 在飞书里互相协作

<grid><column width-ratio="0.500000"><p>不再是一个 Agent 什么都做——多个专业 Agent 在群里分工接力。协作过程对人可见，能插话、能打断、能纠偏。</p><ol><li seq="1">✅ Agent<b> 能 @ 其他 Agent、互相调用——多 Agent 协作最基础的信道已经打通</b></li><li>✅ Agent 能识别群里其他 Bot 的身份和名字——为多 Agent 调度和协作铺路</li></ol><blockquote><p>查看 <cite doc-id="GtniwsJOzirrBEkmDFGcswmMnQg" file-type="wiki" title="飞书 Agent @ Agent 配置指南" type="doc"></cite>了解详情</p></blockquote></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="BOT AT BOT2.mp4" mime="video/mp4" origin-height="2160.000000" origin-width="1700.000000" size="29043627" token="Lpnjbf9fRo9DBtxyrJ5czWTJn2f"/></figure></column></grid>

---

## 二、Agent 在飞书里像人一样收发消息，帮你处理杂活

<grid><column width-ratio="0.500000"><p>你让 Agent 帮你发条消息，Agent 以你的身份操作——发件人显示的是你的名字，消息归属于你，权限也跟着你走。群聊拉人踢人，不用在飞书和 Agent 之间来回切换。</p><ol><li seq="3">✅ Agent 能以你<b>本人名义</b>发消息——同事看到的发件人就是你，不是机器人头像</li><li>✅ Agent 能以你的名义发图片、文件、录音、视频——多媒体也能代发，不只是文字</li><li>✅ Agent 能以你的名义建群——群主直接就是你，不用手动转让</li><li>✅ Agent 能拉人进群、踢人出群——一步到位，不用打开群设置翻半天</li><li>✅ Agent 能给消息加表情回复——已读、赞同、感谢，一个 emoji 搞定</li><li>✅ Agent 能改群名和群描述——项目改名了，群名群描述一起改掉</li><li>✅ Agent 能批量获取消息详情（含发件人和 Thread）——一次拉几十条，省得一条条点</li><li>✅ Agent 能实时监听新消息——有人发消息立刻响应，不用轮询</li><li>✅ Agent 能生成消息链接——可一键跳转消息原文</li></ol></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="bot拉群.mp4" mime="video/mp4" origin-height="2160.000000" origin-width="1700.000000" size="3552960" token="K0n1b3QsfoV3udxC3QucBl6BnCg"/></figure></column></grid>

---

## 三、Agent 直接出活儿——文档、PPT、表格、画板

你对 Agent 说"帮我写个项目方案"，回头一看飞书云文档已经建好了、格式排好了、权限开好了，你直接就能打开编辑。PPT、表格、画板同理——说完就有了。

### 云文档

1. ✅ Agent 能在飞书云文档里**起草、修改**——Markdown 写完自动转飞书格式，不用手动排版
2. ✅ Agent 能按章节替换、按关键词查找、按段落插入——精准编辑，不会把整篇重写
3. ✅ Agent 能从剪贴板直接粘贴截图到文档——不用先存本地再上传
4. ✅ Agent 能把图片和文件**插到文档任意位置**——想放哪放哪，不只是末尾
5. ✅ Agent 能上传任意大小的媒体文件——大视频也行，自动分片上传
6. ✅ Agent 创建的文档你**直接就能打开**——自动授权，不会"无权限"
7. ✅ Agent 能预览文档内的图片和媒体——看清楚再决定要不要改
8. ✅ Agent 插入文件可选**卡片、预览或内嵌**三种展示方式——你说哪种就哪种
9. ✅ **Agent × 文档评论协作**——Agent 能在文档、电子表格、幻灯片、多维表格上加评论，也能响应用户在文档里 @bot 的评论。让 Agent 像同事一样在文档里 review、提建议、回应反馈。

### 画板

<grid><column width-ratio="0.500000"><ol><li seq="21">✅ Agent 能在文档里<b>直接生成可编辑的架构图、流程图</b>——不是截图，是真的能拖能改</li><li>✅ Agent 能把画板导出为图片、Mermaid/PlantUML 代码——想嵌到哪都行</li><li>✅ Agent 能往画板里插入图片——截图、照片直接放进去</li></ol><p></p></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="画板.mp4" comment-refs="c2" mime="video/mp4" origin-height="2160.000000" origin-width="1700.000000" size="5506016" token="W2HRbCUvQoBVxnxdmL4cROrnnFe"/></figure></column></grid>

<table><colgroup><col/></colgroup><tbody><tr><td><b>更多 Agent 创作的飞书画板案例</b><grid><column width-ratio="0.230075"><img name="img_v3_0211i_71af1438-207e-49dc-97c9-baed79dcaa4g.png" alt="图片展示了飞书AI时代人机协作技术栈，分为应用层、工具层、协议层和基础层。应用层有AI专业工作包、人与系统的对话方式；工具层有CLI、MCP、API；协议层有MCP协议、AI时代的通用通信；基础层有API、CLI、MCP、Skill。底部还列出API、MCP、CLI、Skill的定义。该图与上下文紧密相关，是对上文提到的Agent结合飞书CLI新玩法的背景介绍，直观呈现了技术栈构成。" comment-refs="c3" mime="image/png" scale="1.000000" src="JVGpb2wF2ozxWHxY88PcKCM9nsd"/></column><column width-ratio="0.269925"><img name="img_v3_0211i_a089089e-363f-4e28-b64c-fbb6bd21ec2g.png" alt="图片展示的是电商用户转化漏斗，从展示:1" mime="image/png" scale="1.000000" src="WXWjbiNmyoTHIGxRT8Dcarp1njh"/></column><column width-ratio="0.274907"><img name="img_v3_0211i_ec405e72-62b1-46f0-abe5-ae79d40b1f8g.png" alt="这张图片是马斯洛需求层次理论的图示，整体为金字塔结构，从下到上分为五个层次，分别标注为“生理需求”“安全需求”“社交需求”“尊重需求”“自我实现”，对应标注的数字序号从1到5。金字塔各层次旁配有对应需求的简要文字说明，图示左上角标注主题为马斯洛需求层次理论，底部还有相关概念及核心原则的补充说明内容。该图片用于呈现马斯洛需求层次的递进关系，结合上下文可知，其与文档中介绍的Agent相关内容无关，推测是文档排版时的误插入内容。" mime="image/png" scale="1.000000" src="U7Csbv2myoNaL1xxo08cwBFensO"/></column><column width-ratio="0.225093"><img name="img_v3_0211i_f8c70bd3-f211-4abd-911b-55c464e34d5g.png" alt="图片是一张关于济州岛5日漫游手帐的海报。海报上方有“济州岛5日漫游手帐”及英文标题。手帐分为5天行程，包括抵达、东线、西线、中段、中段+。如第一天抵达时有机场落地、老城闲晃等行程，第二天东线有看日出、嬉岛去鸟岛等，还有每日小贴士。底部有“必经美食打卡章”及“推荐路线 人均参考价”等内容。该图片与文档中介绍Agent能创作画板的内容相关，展示了Agent创作的画板案例。" mime="image/png" scale="1.000000" src="TuZTbyYM2oVp8IxdSMvc6rHfnpf"/></column></grid></td></tr></tbody></table>



<grid><column width-ratio="0.500000"><h3>幻灯片</h3><ol><li seq="24">✅ <b>Agent 做 PPT 有 42 套官方模板，覆盖 8 大场景</b>——不再是白底黑字的丑 PPT</li><li>✅ Agent 能精确修改 PPT 里的<b>单个元素</b>——改一句标题不用重做整页</li><li>✅ Agent 能把本地图片直接插进 PPT——不用先传到云空间</li></ol><p></p></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="PPT.mp4" mime="video/mp4" origin-height="2888.000000" origin-width="2160.000000" size="28021936" token="LzBMbDNdbo04Rpx9jRSck7I8n0c"/></figure></column></grid>

<table><colgroup><col/></colgroup><tbody><tr><td><b>更多 Agent 创作的飞书幻灯片案例</b><grid><column width-ratio="0.333270"><img name="exported_img_v3_0211i_02ad03aa-3d33-4ecc-b22c-98d4edcc99cg.jpeg" alt="这张图片是关于AI Agent核心特质的内容讲解，页面主题为“‘数字同事’如何帮你提效？”，介绍了AI Agent的三大核心特质。左侧是由发光线条与节点构成的科技感连接示意图，象征AI Agent的运作逻辑。右侧分三栏逐一说明：第一栏是“任务拆解(Decomposition)”，其功能是将模糊自然语言目标自主拆分为多步计划，比如将准备下周部门会议拆分为定日程、写议程、发通知；第二栏是“工具调用(Tool Use)”，说明AI Agent可按需连接并操作文档、表格、日历等各类办公组件，不再局限于输出文本；第三栏是“跨系统协作(Cross-system)”，指出该能力可打破软件数据壁垒，实现审批系统、IM、知识库间的无缝穿梭，形成完整工作流闭环。" caption="&#xA;" mime="image/jpeg" scale="0.380208" src="WQ4ybSG56oG9Djx857Sc8VW0nle"/></column><column width-ratio="0.333365"><img name="exported_img_v3_0211i_34f33320-e6d7-4a8f-8c1e-2db1abd7fb1g.jpeg" alt="图片展示的是论文“M*: Every Task Deserves Its Own Memory Harness”的内容，核心观点是不要为所有Agent套同一种记忆，而是让任务自己“长出”记忆系统。左侧文字说明论文编号、发表日期及作者，下方框内有“Schema + Logic + Instructions”等内容。右侧以黄色圆圈为中心，周围有“Conversation Entity graph”“Healthcare Checklist”“Legal SQL + RAG”“Embodied Action cache”等板块，呈现不同任务的记忆系统。该图与上下文介绍的Agent结合飞书CLI新玩法相呼应，直观呈现论文观点。" mime="image/jpeg" scale="0.243333" src="PQuRbxYVHoj0GAxkxITc0vWlnyh"/></column><column width-ratio="0.333365"><img name="exported_img_v3_0211i_333add05-d4fa-426a-b4e3-db556f3bd44g.jpeg" alt="这张图片是社团活动策划方案的PPT页面，属于文档中提及的Agent创作的飞书幻灯片案例。页面整体背景为带网格的黑色，中间以醒目的白色字体标注方案名称“社团活动策划方案”，方案上方标注“科技创新社”，下方注明策划人为王梓涵。页面四周分布着风格活泼的彩色几何图形，这类设计符合Agent生成的幻灯片案例特点，对应文档中介绍Agent可直接生成文档、PPT等成果的相关内容。" mime="image/jpeg" scale="0.243333" src="EEQtbfTkNoBLEWxSitPcNZcNndh"/></column></grid><grid><column width-ratio="0.332865"><img name="exported_img_v3_0211i_6ff9373e-fee9-4ef6-a489-f8c66ab4e3dg.jpeg" alt="图片展示了公司介绍、愿景、产品介绍及战略规划等内容。上方是现代化建筑夜景，下方文字介绍公司成立于2018年，累计融资超5亿美元，团队规模突破2000人，分布在北京、上海、深圳、新加坡。产品介绍涵盖智能办公、数据分析、AI应用三大板块。战略规划持续投入研发创新，拥有500余项技术专利，多项技术指标行业领先，获国家级高新技术企业认证。该图与文档中介绍公司相关内容相呼应。" mime="image/jpeg" scale="0.243333" src="AKcabr9kCowNn3xQW72c7ajfncd"/></column><column width-ratio="0.334270"><img name="image.png" alt="图片展示了《增长黑客》一书的封面及核心观点。封面以红色为主色调，书名“增长黑客”醒目，配有“HACKING GROWTH”英文及“HACK”图案。右侧以红色背景呈现核心观点，作者肖恩·埃利斯是增长黑客概念先驱，曾为Dropbox、Eventbrite等独角兽企业提供增长战略顾问服务。核心观点包括AARRR模型（获取、激活、留存、收益、推荐）为产品增长提供分析框架，适用于互联网产品的全生命周期管理，以及通过数次驱动的产品迭代和病毒式传播策略，帮助企业实现低成本、高效率的用户增长。" mime="image/png" scale="0.341760" src="ALCvbMO1Aoc688xkcuFcZBMtnDb"/></column><column width-ratio="0.332865"><img name="模板合集-图片-8.jpg" alt="图片展示的是飞书幻灯片中的一张幻灯片，背景为黑色。左侧上方显示“演讲人：陈晓明”“目标岗位：高级产品经理”，下方有“Promotion Report”字样。右侧是“职位晋升汇报”标题，字体为白色，其中“晋升”二字为紫色，下方标注日期“2026 - 05 - 10”。右侧还有一条白色曲线装饰。此幻灯片可能是陈晓明关于职位晋升的汇报内容。" mime="image/jpeg" scale="0.243333" src="UP6ObmEMAo5BOJxSkp0cCohYngg"/></column></grid><grid><column width-ratio="0.332627"><img name="exported_img_v3_0211i_c5edbf30-55ff-43fc-9dea-1f51b6287d9g.jpeg" alt="图片展示了项目进展的Task Achievement图表。6月有需求梳理、产品制作、技术方案、方案评审、系统集成等任务；7月有原型设计、功能开发、用户招募、案例收集、共创活动等任务；8月有原型设计、功能开发、共创活动等任务。其中，O1为完成产品需求文档梳理与高保真原型设计，通过产品评审；O2为完成核心功能模块开发与内部集成测试，代码质量达标；O3为启动Beta测试招募，收集首批种子用户反馈并迭代优化。该图与文档中项目进展内容相关，直观呈现了各阶段任务安排。" mime="image/jpeg" scale="0.243333" src="Y7rAbj2IuoiQUWxMqg9cUWtBnPh"/></column><column width-ratio="0.334746"><img name="image.png" alt="图片展示了产品经理岗位认知相关内容。背景为紫色，上方有“认知与评价 Cognition and Evaluation”字样。下方左侧是“竞品追踪”板块，包含持续关注行业竞品动态等内容；中间是“产品迭代”板块，提及主导完成3个核心产品模块设计与上线等；右侧是“团队培养”板块，介绍了带领5人小组高效完成年度重点项目等。该图片与上下文介绍产品经理岗位职责的内容相呼应，直观呈现岗位核心能力。" mime="image/png" scale="0.342723" src="F8vobnhBVohW5wxBpfOc7hQ0nOe"/></column><column width-ratio="0.332627"><img name="exported_img_v3_0211i_87828121-0b8b-4c29-810b-b0fc19d8b2ag.jpeg" alt="图片展示了飞书市场分析中的国内市场和国际市场内容。左侧白色圆圈内标注“国内市场”，下方文字说明全球企业服务软件市场持续扩张，欧美市场成熟度高，亚太新兴市场增速领先，出海机遇显著。右侧蓝色圆圈内标注“国际市场”，下方文字指出国内SaaS市场规模达千亿元，年增长率25%，中小企业数字化转型需求旺盛，市场前景广阔。该图与文档中市场分析部分上下文对应，直观呈现了飞书在国内外市场的相关情况。" mime="image/jpeg" scale="0.243333" src="SmBkb8uzZoIqV0xzeIjcPyZ5ngh"/></column></grid></td></tr></tbody></table>

### 多维表格

1. ✅ Agent 能**批量写入或更新**记录——几百条数据一次灌进去
2. ✅ Agent 能指定只返回需要的字段——自动配置视图，省 token 也省眼睛
3. ✅ Agent 能自动排版仪表盘，加 Markdown 文字说明——给团队看的报表直接成型
4. ✅ Agent 能批量下载附件——不用一条一条点
5. ✅ Agent 能把 Base 导出为 `.base` 文件备份——也能导回，**数据搬迁不丢东西**
6. ✅ Agent 能一键生成记录分享链接（单条或批量）——分享给谁直接发链接
7. ✅ Agent 创建或复制的 Base 你直接能操作——自动授权，不用找管理员
8. ✅ Agent 能一步**生成表单和题目**——活动报名、用户反馈、满意度调查，说完就有
9. ✅ Agent 读取 Base 数据**输出 Markdown 格式**——给 LLM 看更高效
10. ✅ Agent 能管理多维表格的**自动化流程**（Workflow）——记录变了自动通知、自动更新

### 电子表格

1. ✅ Agent 能读写单元格、追加数据——Excel 式操作在飞书表格上一步搞定
2. ✅ Agent 能往单元格里插图片——数据可视化一步到位
3. ✅ Agent 能在表格里**自由放置浮动图片**——不受单元格限制
4. ✅ Agent 能增删行列、合并拆分、查找替换、设置样式——表格常用操作全覆盖
5. ✅ Agent 能批量管理下拉选项——几十个选项不用一个个加
6. ✅ Agent 能管理工作表：新建、复制、删除、重命名——多 Sheet 管理一句话搞定

### 云空间

1. ✅ Agent 能上传下载文件、创建文件夹、设置权限——云空间管理一句话搞定
2. ✅ Agent 能上传**任意大小**的文件——超 20MB 自动分片上传，不怕大文件
3. ✅ Agent 下载文件**自动识别扩展名**——拿到就能打开，不用手动改后缀
4. ✅ Agent 能一步完成文件**导入导出、格式转换、目录移动**——不用三个步骤分开做
5. ✅ Agent 能批量统一文件名、创建快捷方式——整理强迫症的福音
6. ✅ Agent 能一键清理废弃文件——不用一个个翻哪些该删
7. ✅ **Agent 能在本地文件夹和云空间之间双向同步**（push / pull / status）——像 Git 管代码一样管文档
8. ✅ Agent 能在云空间**创建、下载、编辑** Markdown 文件——纯文本工作流无缝衔接
9. ✅ Agent 上传文件能直接指定知识库节点——传完就归档，不用再手动移
10. ✅ Agent 能向文档所有者**发起权限申请**——你让 Agent 去要权限，不用自己点

### 知识库

1. ✅ Agent 能读取知识库、创建和整理节点——知识库维护不用人盯
2. ✅ Agent 能创建和删除知识空间——新团队来了？一句话开好知识库
3. ✅ Agent 能批量添加移除知识库成员——几十人入组不用一个个点
4. ✅ Agent 创建知识库节点后**自动拥有权限**——不会创建完自己没法看

---

## 四、Agent 帮你开会——从参会到纪要到任务，开完会事就办了

你开完一小时的会，打开飞书发现纪要已经写好了、待办已经建了、下周的跟进日历已经排了。

### 妙记 / 视频会议

1. ✅ Agent 能读取妙记逐字稿，**提取决策和待办事项**——开完会不用再人肉整理
2. ✅ Agent 能一句话**汇总所有会议纪要，输出结构化周报**——一周开了十个会也不怕
3. ✅ **Agent 能把任意音视频文件变成妙记**——录音笔、Zoom、手机录的都行，不限飞书会议
4. ✅ Agent 能提取妙记 AI 产物：**总结、待办、章节**——AI 整理的你直接拿走
5. ✅ Agent 能一步下载妙记音视频——存到本地想怎么用怎么用
6. ✅ Agent 能根据**日历事件或会议 ID** 拿到对应妙记——不用在妙记列表里翻

### 日历

1. ✅ **Agent 能查所有参会者日历、考虑时区、推荐时段、一步建好会议**——大家都没空也会推荐入会概率最大的时间块并说明理由
2. ✅ Agent 能修改日程（标题、时间、描述、增减参会人和会议室）——改一个细节不用重建
3. ✅ Agent 能搜索日程，**一次查找多个会议室**——找间空会议室不用一个个点
4. ✅ Agent 能获取日程分享链接——发给外部参会者一键加入
5. ✅ Agent 能自动生成**当日日程 + 未完成任务摘要**——早上打开就知道今天干嘛



---

## 五、Agent 管你的日常——邮件、审批、任务、OKR、考勤，不用打开 App

你的邮件、审批、待办、OKR、考勤散落在飞书的四个入口里。现在跟 Agent 说一句话，它帮你全处理了——发邮件、批审批、建任务、查考勤，不用打开任何一个 App 页面。

### 邮件

1. ✅ Agent 能扫描未读邮件、**分类摘要、起草回复**——早上一堆邮件不用一封封手动处理
2. ✅ Agent 写邮件引用本地图片会自动上传——不用手动传附件
3. ✅ Agent 发邮件能请求**已读回执**——知道对方看没看
4. ✅ Agent 能发**大附件邮件**——几十 MB 也没问题
5. ✅ Agent 能管理**邮件模板**——周报、通知不用每次重写
6. ✅ Agent 能把邮件分享到**群聊或私聊**——重要邮件一键同步到群
7. ✅ Agent 发邮件能直接附上日历邀请——约会议连邮件带日程一起发
8. ✅ Agent 能**定时发邮件**——写好了定个时间，到点自动发
9. ✅ Agent 能 **24 小时内撤回**已发邮件——发错了还能救
10. ✅ Agent 能使用**个性化邮件签名**——不同场景用不同签名
11. ✅ Agent 能用**别名身份**发信——支持公共邮箱或邮件组发信
12. ✅ Agent 能**管理收信规则**——设好了邮件自己归位
13. ✅ Agent 能实时监听新邮件到达——重要邮件一来就通知你
14. ✅ Agent 能读取**完整邮件会话**——一个 thread 里的来回全看到

### 审批

1. ✅ Agent 能查询、同意、拒绝、转交、撤回、抄送审批——**六种操作一句话搞定**
2. ✅ Agent 能**催办**未处理的审批，查看发起记录——催人不用自己去 @
3. ✅ Agent 能在审批流程中加签和退回——流程不够灵活？现在可以了

### 任务

<grid><column width-ratio="0.500000"><ol><li seq="85">✅ <b>任务成员可以是 AI 智能体——Agent 不只是工具，是你的同事</b></li><li>✅ Agent 能从妙记或对话<b>识别待办事项，自动建任务</b>——说过的事不会丢</li><li>✅ Agent 能搜索任务、设置<b>父子关系</b>、按分组归类、订阅变更——任务管理该有的都有</li><li>✅ Agent 能把任务添加到清单的指定分组——归类到位，不会乱</li><li>✅ Agent 能给任务<b>上传附件</b>——做完的活直接挂在任务上</li></ol><p></p></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="任务-2341.mp4" mime="video/mp4" origin-height="2880.000000" origin-width="2160.000000" size="39621775" token="TQhpbOrUAofHXfxGyCXchzYlnAf"/></figure></column></grid>

### OKR

1. ✅ Agent 能读取和管理你的 OKR——查看目标进度不用打开 OKR 页面
2. ✅ Agent 能新建、查看、更新、删除 OKR **进展记录**——写 OKR 周更不用手动填

### 考勤

1. ✅ Agent 能一句话查出你的**迟到、缺卡、加班记录**——月底核对考勤不用翻 App

---

## 六、Agent 帮你找东西

跨业务域的搜索能力——文档、邮件、人，都能精准定位。

1. ✅ Agent 能搜聊天记录——按关键词、发件人、时间范围、@ 了谁筛选，长聊天记录也能扫完
2. ✅ Agent 找文档能按"**我创建的 / 我编辑的 / 我浏览的 / 我评论的**"筛——不用记是哪天哪类
3. ✅ Agent 能按关键词、编辑时间、创建人**搜索云文档**——几千份文档也能快速定位
4. ✅ Agent 搜索文档支持**高级筛选语法**——精准定位，不用在一堆结果里翻
5. ✅ Agent 能按关键词、参与人、时间**搜索会议录制**——几百个妙记也能精准定位
6. ✅ Agent 能**翻页浏览邮件摘要列表**——几百封邮件也能快速扫
7. ✅ Agent 能按姓名或邮箱**查找同事**——一次搜多个并行返回
8. ✅ Agent 能按"聊过天的人""外部联系人"等条件**高级筛选通讯录**——精准定位要找的人

---

## 七、Agent 接入飞书——一行命令，15 个业务域全部就绪

一行命令完成 CLI 安装、应用创建、授权——你的 Agent 立刻拥有以上全部能力，不用读文档、不用配置 webhook、不用申请权限。

<grid><column width-ratio="0.500000"><ol><li seq="100">✅ MIT 开源，<code>npx @larksuite/cli@latest install</code><b>一行命令安装</b>——不用编译、不用配环境</li><li>✅ <b>跨平台一键安装</b>——macOS / Linux / Windows 都行</li><li>✅ <b><code>lark-cli update</code></b><b> 一行命令更新</b>，支持验证和回滚——升级出问题一秒退回</li><li>✅ CLI 启动<b>自动检测新版本</b>并提示——不会用着过期版本不知道</li><li>✅ 任何命令后加 <code>--jq</code><b>直接提取所需字段</b>——省 token，给 LLM 吃结构化数据</li><li>✅ 飞书事件<b>实时订阅</b>（WebSocket 长连接）——消息、日历、文档变更立刻响应</li><li>✅ <code>lark-cli schema</code> <b>查看任何飞书 API 的参数和权限要求</b>——开发时不用切换文档</li><li>✅ 配套 <b>AI Agent Skills 体系</b>（<code>npx skills add larksuite/cli</code>）——把常用操作封装成 Skill，Claude Code 等 AI 编程工具可直接调用</li></ol></column><column width-ratio="0.500000"><figure view-type="Preview"><source name="跨平台一键安装_macOS.mp4" mime="video/mp4" origin-height="2160.000000" origin-width="1700.000000" size="8995812" token="SXJ7bKyKHot6VZxr5zPcGv5znDg"/></figure></column></grid>

---

## 八、Agent 在飞书里做事，安全有兜底

### 通过开源 CLI 直接可用

1. ✅ **严格模式**：Agent 的 bot / user 身份**可精细配置**——不会越权，做什么身份干什么事
2. ✅ Agent 创建的文件**自动授权给你**——不会出现"我让 Agent 创建的文件我自己没权限"

### 飞书平台侧的安全与治理

> 适用于 Agent 运行在飞书承接链路内的场景，部分能力面向商业化版本或特定部署形态提供。

1. ✅ Agent 的内容有**底线安全检测**：提示词防注入、敏感数据脱敏——AI 生成的内容不会出格
2. ✅ Agent 的行为有**风控**：平台对关键调用行为提供风险监测与异常识别能力——不会被恶意利用
3. ✅ Agent 访问你的资源**遵守你本人的访问权限**——Agent 看不到你看不到的东西
4. ✅ Agent 的关键动作有**审计日志**：支持审计留痕与查询，便于事后追溯——出了事能查到
5. ✅ **OAuth Device Flow + 无密应用创建**——安全接入不用管理密钥

---

# 立即体验

<callout emoji="🚀">
**想体验？** 一行命令开始：`npx @larksuite/cli@latest install`
**了解更多详情**：[**飞书 CLI 官网**](https://www.feishu.cn/feishu-cli) **｜** [**GitHub**](https://github.com/larksuite/cli)  **｜** [**使用指南**](https://bytedance.larkoffice.com/docx/WnHkdJQM6oGpQFxm9i7ckVdenSh)
</callout>

加入 CLI 反馈群交流或订阅更多更新

<chat_card name="飞书 CLI 交流互助群（2 群） ｜Lark CLI Communication &amp; Support (Group2)" chat-id="oc_b12927e59ee30de4fbc4b8b0d5adfc96"></chat_card>
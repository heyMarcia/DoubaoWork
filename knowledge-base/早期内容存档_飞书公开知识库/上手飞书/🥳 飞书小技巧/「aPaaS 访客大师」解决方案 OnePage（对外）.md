<title>「aPaaS 访客大师」解决方案 OnePage（对外）</title>

# 产品简介

访客大师是一款智能化的访客管理系统，可安全便捷地预约来访、接待访客；此外，访客大师后台可以分析、查询访客记录。

**访客大师核心功能：**

- 自助预约：员工可随时在「飞书」小程序「访客大师」内，提前向来访者发起邀约；
- 扫码签到：访客在前台，可直接扫描邀请二维码完成签到，告别冗长登记流程，节省访客等待时间；
- 后台管理：查看访客记录，管理访客签到状态，查看/修改工区订阅人，查看访客热力图。



# 业务流程

<whiteboard token="IfAdwcW0MhGKb1bl2wScPptTn3d"></whiteboard>

业务流程说明：

- 访客创建后，默认的来访状态为待来访。
- 访客默认最长来访时间为一天，因此需要有一个定时任务修改访客记录。

  - 如果访客已签到，则将访客记录修改为已结束
  - 如果访客未签到，则将访客记录修改为已爽约。



# 功能演示

应用实际运行效果：

<table><colgroup><col/><col/><col/><col/></colgroup><thead><tr><th>序号</th><th>场景</th><th>录屏演示</th><th>功能说明</th></tr></thead><tbody><tr><td>1</td><td>桌面端</td><td><figure view-type="Preview"><source name="桌面端.mp4" mime="video/mp4" origin-height="2012.000000" origin-width="3832.000000" size="13365652" token="OnelblBigoJqeGxhbsHcq3DVngb"/></figure></td><td><ul><li>查看预约记录，支持展开查看详情</li><li>支持对预约记录的筛选</li><li>支持对办公点的新建、批量新建、编辑删除</li><li>支持对工区的来访信息订阅，订阅后，有新增访客会通知订阅人</li><li>支持查看访客热力图</li></ul></td></tr><tr><td>2</td><td>新增访客</td><td><figure view-type="Preview"><source name="新增访客预约.MP4" mime="video/mp4" origin-height="1920.000000" origin-width="886.000000" size="31664357" token="UkWjbtQTaoh8Nbxj8Moc7s21nXe"/></figure></td><td><ul><li>日期不能选择当前时间之前</li><li>日期不能选择 7 天之后</li><li>错误信息及提示信息都有 Toast 提示</li><li>邀请明细中不能用重复邮箱</li><li>修改重复邮箱后错误消失</li></ul></td></tr><tr><td>3</td><td>访客详情</td><td><figure view-type="Preview"><source name="访客详情页.MP4" mime="video/mp4" origin-height="1920.000000" origin-width="886.000000" size="19079615" token="TU1JbrjgQoeIhkxDN9nchoqFnpg"/></figure></td><td><ul><li>访客列表前方有数字展示</li><li>访客来访状态颜色区分<ul><li>即将来访</li><li>来访中</li><li>其他状态均为灰色</li></ul></li><li>已签到访客访客可查看进度</li><li>添加访客、修改、撤回按钮仅在 即将来访 时可用</li><li>来访已结束/已取消/已爽约后，需展示「再次预约」功能，功能可用</li></ul></td></tr><tr><td>4</td><td>邮件发送</td><td><img name="image.png" alt="图片展示的是ByteDance公司发送给访客赵宜哲的欢迎邮件。邮件内容包括访客姓名、公司、预约时间、办公地点、接待人员等信息，还提供了访客二维码。邮件由VM &lt;vm@larktest.com&gt; 发送，收件人为赵宜哲。邮件中还提示“Here is your visitor code:”，并附有二维码。该图片与文档中“输入访客码签到”场景相关，说明访客可通过短信、邮件内的访客码完成签到。" mime="image/png" scale="1.000000" src="UNmybR8ViooxlTxnlFrcvEesnOf"/></td><td><ul><li>新增访客时，需要向访客邮箱发送邮件</li><li>邮件中必须包含基础信息及签到二维码</li></ul></td></tr><tr><td>5</td><td>访客出示访客二维码，门卫扫描二维码签到</td><td><figure view-type="Preview"><source name="访客签到.MP4" mime="video/mp4" origin-height="1920.000000" origin-width="886.000000" size="24093029" token="Os3uby9auoKEvkxNoPNcUhIInce"/></figure></td><td><ul><li>页面顶部标题为「扫码签到」</li><li>点击扫码按钮唤起弹窗</li><li>弹窗内包含访客信息和确认签到按钮</li><li>扫码后修改访客的签到状态</li><li>签到弹窗内包含当前的定位信息</li><li>签到成功后，按钮变为签到完成，并返回 Toast 提示「签到成功」</li><li>签到成功后，弹窗过一段时间再消失</li></ul><br/>扫码功能可使用 组件库：<a href="https://ae.feishu.cn/solution/showcase?navId=nav_pane_tj2p0hecrje">ae.feishu.cn</a><img name="ScreenShot_20231109_102615@2x.png" alt="图片展示的是飞书通用组件库中“扫码器 Code Scanner”的页面。左侧导航栏中“扫码器”选项被红色数字2标记突出显示。右侧主内容区域介绍该组件可通过摄像头扫码，支持二维码和条形码。下方“用法示例”部分有“演示”和“配置”选项，当前选中“演示”，下方有“扫码结果”输入框。该图片与文档中扫码功能可使用组件库的内容相关，直观呈现了扫码器组件的使用说明及示例。" mime="image/png" scale="0.145053" src="KbCAb1NlPoKi12xCWimcfIOxnbb"/><br/>组件库安装链接：<a href="https://ae.feishu.cn/ae/isv/componentLib/install/token/992a72522b88e84ba9c4c5b897d75783">ae.feishu.cn</a></td></tr><tr><td>6</td><td>输入访客码签到</td><td><img name="image.png" alt="图片展示的是输入访客码签到界面。背景为渐变的蓝绿色，中间偏上位置有蓝色椭圆形按钮，上面白色文字写着“点击扫码签到”。下方偏下位置也有一个蓝色椭圆形按钮，上面白色文字写着“输入访客码签到”。该图片与文档中“输入访客码签到”部分内容对应，直观呈现了输入访客码签到时的界面样式，帮助用户了解操作入口。" mime="image/png" scale="1.000000" src="Qm96bhd0DobVaDxl7Pwc1gBQnPb"/><img name="image.png" alt="图片展示的是输入访客码签到的弹窗界面。背景为渐变蓝绿色。弹窗上方有“点击扫码签到”文字及蓝色图标。弹窗内标题为“请输入访客六位来访码”，下方有一个输入框，提示“请输入通过短信或邮件收到的来访码”。底部有一个蓝色的“确认签到”按钮。该图片与文档中“输入访客码签到”内容对应，直观呈现了输入访客码签到时弹窗的样式和布局。" mime="image/png" scale="1.000000" src="K00Ub9ekhokiBixUKnqcdnChnKh"/></td><td>支持用户通过短信、邮件内的访客码，完成签到。</td></tr><tr><td>7</td><td>邀约人帮助签到</td><td><figure view-type="Preview"><source name="帮助访客签到.MP4" mime="video/mp4" origin-height="1560.000000" origin-width="720.000000" size="6483195" token="CS0LbzoSJohdIfxdyqkcip2cnHc"/></figure></td><td><ul><li>在预约详情页面，可以帮助访客出示二维码，出示访客信息，可供扫描</li><li>扫描后修改访客记录</li><li>点击隐藏二维码后，刷新数据</li></ul></td></tr><tr><td>8</td><td>再次预约</td><td><figure view-type="Preview"><source name="再次预约.MP4" mime="video/mp4" origin-height="1920.000000" origin-width="886.000000" size="15093818" token="Qj04bwOxrotoNtxpdtdcKPx7nmf"/></figure></td><td><ul><li>点击再次预约，需要弹出 Toast 提示</li><li>表单加载完后，自动补充基于发起记录的访客数据</li><li>其他校验遵循新建记录</li><li>邀请明细中不能用重复邮箱</li></ul></td></tr><tr><td>9</td><td>URL在飞书中解析</td><td><figure view-type="Preview"><source name="20231006-191214.mp4" mime="video/mp4" origin-height="1280.000000" origin-width="576.000000" size="2792361" token="VR29b80B1ok9QqxlAdGczc2knjo"/></figure></td><td>复制预约详情页URL，发送在飞书后能自动解析成卡片。</td></tr><tr><td>10</td><td>访客通知订阅人</td><td><img name="image.png" alt="图片展示的是飞书中“访客大师”机器人发送的消息卡片。卡片上方显示“有新的访客来访，请注意接待”。卡片内具体信息包括预约人为@赵宜哲，来访工区是浙大森林，来访时间为2023 - 09 - 07 17:13:00，来访人数为2人，下方还有“查看详情”按钮。此图片与文档中“新增访客后，需要按照通知订阅中的人员，发送消息卡片提醒”的内容对应，呈现了访客通知的消息卡片样式。" mime="image/png" scale="1.000000" src="GE3RbnDjjostjaxlLO9cPPpQnSd"/></td><td>新增访客后，需要按照通知订阅中的人员，发送消息卡片提醒。</td></tr></tbody></table>
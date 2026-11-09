# W45 S/A评级复核

窗口：2026-11-02—2026-11-08。未获复核前不生成正式周报。

|评级|事件|日期|相关/影响/新颖|总分|
|---|---|---|---|---|
|S|ESA更新ERMIS-3自主星地光链路运行及处理载荷进展|2026-11-02|5/4/4|4.50|
|S|NASA宣布月基地运输与技术任务采购组合|2026-11-07|4/5/4|4.30|
|A|中科星云太空智能完成工商登记，注册资本15亿元|2026-11-02|5/3/3|4.00|
|A|Northwood宣布完成3.75亿美元C轮融资|2026-11-02|4/4/4|4.00|
|A|地卫二与阿曼兰斯签署太空人工智能协议|2026-11-02|5/3/4|4.20|
|A|Tumbleweed宣布690万欧元种子轮融资|2026-11-03|4/3/4|3.70|
|A|力箭二号遥二将18颗千帆组网卫星送入轨道|2026-11-03|4/4/3|3.80|
|A|NASA披露SSPICY任务通信无法恢复|2026-11-03|4/4/4|4.00|
|A|千公里空芯光纤完成128Tb/s双向实时传输验证|2026-11-04|4/4/4|4.00|
|A|国星宇航启动香港公开招股，计划11月13日上市|2026-11-05|5/3/4|4.20|
|A|国际空间站完成第八块IROSA太阳翼安装|2026-11-05|4/3/4|3.70|
|A|Blue Origin发布Northstar助推发动机|2026-11-05|4/4/4|4.00|
|A|New Glenn新增GS3第三级方案|2026-11-05|4/4/4|4.00|
|A|Orbital拟采用Orca星载自主软件|2026-11-05|5/3/3|4.00|
|A|DARPA披露NOM4D自动在轨桁架组装演示|2026-11-05|4/4/4|4.00|
|A|Firefly与AST达成超过13亿美元发动机及许可协议|2026-11-06|3/5/4|3.80|
|A|谷神星二号遥三四星入轨并部署星眼01载荷|2026-11-07|4/4/4|4.00|

## S · ESA更新ERMIS-3自主星地光链路运行及处理载荷进展

ESA称8U ERMIS-3与希腊Holomondas地面站建立光链路，系统现自主运行、每日两次昼夜链路，具有最高10Gbps链路余量；卫星另搭处理IP核、压缩算法及自主控制。高光谱数据快速传输仍是后续演示目标。

判断：自主光链路与处理载荷披露连接星上处理和数据下行，但10Gbps是链路余量表述，非持续吞吐实测。

对我们的意义：索取端到端处理、压缩及下行数据，识别瓶颈发生在何处。

后续跟踪：高光谱业务演示、实际吞吐、误码率、昼夜可用率。

来源：https://resilience.esa.int/archives/news/greek-optical-communications-demonstration-cubesat-ermis-3-makes-high-performance-debut-space-to-ground-link

核验边界：11月2日为运行状态披露日，首光确切日未给；3月30日发射不是本周事件。10Gbps为margin表述，不能写成已持续实测吞吐。；核验底稿：evidence/w45-adj-open-esa2.json；核验底稿：evidence/w45-adj-open-esa2.json

## S · NASA宣布月基地运输与技术任务采购组合

NASA授予8家企业CLPS2十年框架，合计上限100亿美元；同时推进PROMISE核电月球车及Blue Origin交付合同，并公布VADR任务订单。PROMISE计划搭载耐辐射HPSC及自主算法。

判断：月基地采购组合包含HPSC及自主任务方向，是需求侧信号；框架上限不是已承诺采购，处理器仍未部署。

对我们的意义：跟踪耐辐射计算、能源与自主控制能否转成独立可竞标任务。

后续跟踪：任务订单、处理器资格、承包商分工及实际预算义务。

来源：https://www.nasa.gov/news-release/nasa-awards-moon-base-transportation-technology-science-projects/

核验边界：框架上限不是已承诺支出；PROMISE计划2028年末发射，不是已部署HPSC。一个公告采购组合不按子条款重复计数。；核验底稿：evidence/w45-us-open-nasa-awards.json

## A · 中科星云太空智能完成工商登记，注册资本15亿元

公告确认参股公司11月2日完成工商登记，注册资本15亿元。这不是已到账融资额；公告同时提示核心技术尚未大规模在轨工程验证。

判断：参股公司设立是产业协同组织节点，注册资本不能当作融资到账或已具备工程能力。

对我们的意义：观察芯片、卫星与地面算力股东如何落实联合产品与采购。

后续跟踪：实缴资本、首批工程任务、在轨验证与可核验客户收入。

来源：https://vip.stock.finance.sina.com.cn/corp/view/vCB_AllBulletinDetail.php?CompanyCode=82772411&gather=1&id=12690070

核验边界：来自企查查境内清单第129行；行业归属Space_Compute;Commercial_Space；日期为数据库记录日，不保证等于交割日。来源标题：；Raw金额与21列标准化保留，公开来源补核尚未完成。；核验底稿：input/境内融资清单_2026-W45_标准化.csv；三类实际检索审计：evidence/fin-source-root-35.json；阶段3公开来源补核，公开披露日与数据库记录日区别保留；核验底稿：evidence/stage3-fin-open-xingyun.json

## A · Northwood宣布完成3.75亿美元C轮融资

公司宣布完成3.75亿美元C轮融资，用于卫星地面网络建设、现有合同交付与招聘；另有信贷安排，不与本轮股权融资金额混加。

判断：地面网络C轮融资强化数据通道资源，股权融资与信贷安排需分开计算。

对我们的意义：评估共享站网能否降低数据下行和作业调度成本。

后续跟踪：站点交付、合同履约、有效带宽、利用率与价格。

来源：https://www.northwoodspace.io/blog/northwood-series-c

核验边界：来自企查查境外清单第44行；行业归属Commercial_Space；日期为数据库记录日，不保证等于交割日。来源标题：Northwood Space获3.75亿美元C轮融资；Raw金额与21列标准化保留，公开来源补核尚未完成。；主来源已补为匹配的公开披露；原始清单未改写，公开口径差异以本条摘要说明。；核验底稿：evidence/finance-open-northwood.json；三类实际检索审计：evidence/fin-source-root-46.json

## A · 地卫二与阿曼兰斯签署太空人工智能协议

11月2日签署合作协议，首批星座规模预计20星，并计划共建阿曼卫星AIT中心、联合太空AI实验室与人才培训；10月已发布的阿曼双星为历史背景。

判断：太空AI合作协议明确星座及实验室方向，但20星规模属于预期而不是已部署。

对我们的意义：跟踪海外伙伴的任务需求、数据主权与本地交付接口。

后续跟踪：后续正式订单、AIT中心建设、星载处理规格和首批任务。

来源：https://star.vision/zh-CN/newsroom/105

核验边界：金额未公开；20星属于协议预期，不能称已发射。签约与政府北斗MOU独立。浙江日报11月4日稿交叉验证。；证据：evidence/w45-cn-extra-open-7.json；核验底稿：evidence/w45-cn-extra-open-7.json

## A · Tumbleweed宣布690万欧元种子轮融资

公司11月3日宣布690万欧元种子轮，由PactVC领投，用于2027年三次任务及2028年返回平台开发；返回能力仍为计划，7月首飞不是本周新发射。

判断：融资支持微重力平台扩展，是载荷部署资源信号；2028年返回能力仍是计划。

对我们的意义：跟踪标准载荷容器的供电、数据及验收接口，不将公司成本优势口径当独立测算。

后续跟踪：2027年任务、客户载荷交付及返回平台工程试验。

来源：https://www.tumbleweed.com/press-kit

核验边界：来自企查查境外清单第51行；行业归属Commercial_Space；日期为数据库记录日，不保证等于交割日。来源标题：Tumbleweed筹集了创纪录的690万欧元种子轮，将微重力研究带给大众；Raw金额与21列标准化保留，公开来源补核尚未完成。；核验底稿：input/境外融资清单_2026-W45_标准化.csv；三类实际检索审计：evidence/fin-source-root-50.json；阶段3公开来源补核，公开披露日与数据库记录日区别保留；核验底稿：evidence/stage3-fin-open-tumbleweed.json

## A · 力箭二号遥二将18颗千帆组网卫星送入轨道

11月3日08时15分由东风商业航天创新试验区发射，完成首个卫星互联网大规模组网任务；首次使用的多星解锁分离装置与任务参数合并记录。

判断：18颗组网卫星入轨增加载体规模，不直接证明星载计算业务交付。

对我们的意义：观察组网与数据回传资源，比较计算载荷部署窗口。

后续跟踪：卫星健康状态、网络接入及后续批次部署。

来源：https://stcsm.sh.gov.cn/xwzx/mtjj/20261105/ac011765ffa9487494764e16fde81ef9.html

核验边界：与官网因超时未解析的同一任务合并；不把18星、分离装置和第99次院任务拆行。；证据：evidence/w45-cn-open-3.json；核验底稿：evidence/w45-cn-open-3.json

## A · NASA披露SSPICY任务通信无法恢复

NASA与Starfish确认Otter在调试阶段失去双向通信且不可恢复；故障保护软件使无线电错误关闭。失联发生日未明确，本周节点是任务结论披露。

判断：Otter失联结论显示软件配置与故障保护可成为在轨服务单点风险，不能视为自主检查技术已完成验证。

对我们的意义：把通信断电、遥测可恢复性和安全模式纳入算力卫星可靠性清单。

后续跟踪：独立故障复盘、软件修正及后续任务冗余设计。

来源：https://www.nasa.gov/blogs/smallsatellites/2026/11/03/nasa-funded-sspicy-mission-experiences-communications-loss/

核验边界：已发生的故障结论；不能将原定碎片检查、自主导航与机械臂能力写成完成验证。；核验底稿：evidence/w45-us-open-1076.json

## A · 千公里空芯光纤完成128Tb/s双向实时传输验证

11月4日报道联合完成1007.48公里空芯光纤试验，扩展C+L波段、单波800Gb/s，单纤双向总容量128Tb/s；11月7日央视稿补充单程3.43毫秒及算力网应用。

判断：长距离空芯光纤实测降低地面传输时延，为星地协同提供链路成本与时延参照，并非星间激光验证。

对我们的意义：对照地面优质链路与星上预处理节省的带宽、时延价值。

后续跟踪：可重复测试、商用距离、设备兼容与部署成本。

来源：https://finance.eastmoney.com/a/202611043921981854.html

核验边界：试验确切完成日未披露，以本周首次可确认公开披露日记录；11月4日与7日为同一实验，不重复。；证据：evidence/w45-cn-extra-open-4.json；核验底稿：evidence/w45-cn-extra-open-4.json

## A · 国星宇航启动香港公开招股，计划11月13日上市

报道披露全球发售约3012.1万股、预计募资总额8.75亿港元；这是招股计划，不代表已完成上市或募集资金到账。

判断：招股启动为太空数据主体提供资本与经营披露窗口，不代表上市或融资到账已完成。

对我们的意义：优先核查收入结构、客户集中度、在轨服务成本与募资用途。

后续跟踪：最终定价、上市交割、募资净额及后续经营披露。

来源：https://stock.10jqka.com.cn/20261105/c681488043.shtml

核验边界：与W44通过聆讯为不同交易节点；不得将预期上市日期当成本周已完成节点。；核验底稿：evidence/finance-open-adaspaceipo.json

## A · 国际空间站完成第八块IROSA太阳翼安装

NASA确认宇航员完成6小时59分钟舱外活动，安装并展开最后一块IROSA；整套升级将空间站发电能力由160千瓦增至约215千瓦。

判断：太阳翼安装是载荷供电条件的变化，不等于新增计算载荷已投用。

对我们的意义：跟踪轨道平台功率余量及可分配载荷资源。

后续跟踪：展开调试、并网和新增载荷供电预算。

来源：https://www.nasa.gov/blogs/spacestation/2026/11/05/spacewalkers-install-final-roll-out-solar-array/

核验边界：与开始舱外活动、次日清理工作合并为一个完成节点。；核验底稿：evidence/w45-us-open-iss-complete.json

## A · Blue Origin发布Northstar助推发动机

公司发布LOX/LNG发动机Northstar，标称推力71.5万磅，并披露减重和增材制造设计；公司称项目已进入开发测试。

判断：新发动机发布体现运载平台路线演进，尚非本周完成飞行验证。

对我们的意义：按试验成熟度与交付节奏评估未来算力载荷可获得的运力。

后续跟踪：全工况试验、定型、首飞安排及复用可靠性。

来源：https://www.blueorigin.com/news/introducing-northstar-new-booster-engine

核验边界：推力与制造参数为公司披露；不是完成资格认证或飞行验证。；核验底稿：evidence/w45-us-open-1150.json

## A · New Glenn新增GS3第三级方案

Blue Origin发布采用BE-7发动机的GS3第三级，面向GEO直达及地月任务，并披露复合液氢贮箱压力试验；首项政府地月任务计划2028年发射。

判断：新增第三级方案可能扩展任务范围，产品方案不代表飞行能力已兑现。

对我们的意义：区分高能轨道部署需求与低轨计算载荷的成本最优解。

后续跟踪：工程验证、首次客户任务、质量与运力约束。

来源：https://www.blueorigin.com/news/new-glenn-expands-reach-with-gs3

核验边界：发布与贮箱测试不等于第三级飞行成功。与Northstar为不同产品稿。；核验底稿：evidence/w45-us-open-1151.json

## A · Orbital拟采用Orca星载自主软件

Payload报道双方意向书拟为数据中心卫星集成Orca自主系统，包括小模型建议、规则指令转换与安全内核；计划2028年随Orbital-1飞行，部分或于2027年先测。

判断：星载自主软件意向书指向计算卫星运行安全接口，但不是已交付服务或在轨演示。

对我们的意义：比较模型建议与安全内核之间的权限隔离及责任边界。

后续跟踪：正式合同、软件测试、飞行搭载及在轨任务日志。

来源：https://payloadspace.com/exclusive-orbital-taps-orca-aerospace-for-onboard-autonomy-software/

核验边界：意向书而非正式部署；最多2000万美元为报道合同潜值，不记融资；当前仅采访报道未取得公司原稿。；核验底稿：evidence/w45-us-open-orbitalorca.json

## A · DARPA披露NOM4D自动在轨桁架组装演示

DARPA宣布Caltech载荷在轨将零件组装为桁架并同步部署反射网，验证大型空间结构组装概念；载荷由Momentus Vigoride承载。

判断：自动桁架组装为大型空间设施提供结构制造实证，但原文未称AI算法突破。

对我们的意义：将大结构装配视为空间数据中心工程条件之一，独立核查供电散热。

后续跟踪：结构精度、长期稳定性、可扩展规模与后续在轨试验。

来源：https://www.darpa.mil/news/2026/nom4d-program-demonstrates-automated-in-space-assembly

核验边界：本周是成果披露，具体组装日期未给出；原稿明确不依赖复杂机器人或先进算法，不应包装成AI突破。；核验底稿：evidence/w45-us-open-nom4d.json

## A · Firefly与AST达成超过13亿美元发动机及许可协议

Firefly披露协议含27台Miranda、9台Vira发动机及三年IP许可和工程支持，供AST前三枚重型火箭使用。

判断：发动机及许可协议改变航天供应链资源配置，13亿美元协议规模不能直接记作已确认收入。

对我们的意义：关注卫星业务向关键推进系统延伸后的供应保障与资本开支约束。

后续跟踪：合同执行、交付里程碑、许可条件及客户回款。

来源：https://fireflyspace.com/news/firefly-aerospace-signs-rocket-engine-deal-valued-at-more-than-1-3-billion-with-ast-spacemobile/

核验边界：商业供应链合同而非融资；对价含现金及股票，不应写成全部现金已到账。；核验底稿：evidence/w45-us-open-306.json

## A · 谷神星二号遥三四星入轨并部署星眼01载荷

11月7日07时37分谷神星二号遥三从酒泉发射，将观澜试验星、云遥一号28星、中北大学一号、钧天一号06A（星眼01星）送入轨道。星眼配备广域监视相机及星上算力单元，后续拟验证星上解算与地面协同。

判断：四星发射与星眼载荷部署扩展遥感和态势感知载体；部署不等于全部能力完成验证。

对我们的意义：评估星载感知处理与地面任务调度接口，避免按入轨数量推算算力。

后续跟踪：载荷调试、首批数据、处理时延和服务对象。

来源：https://www.chinanews.com/gn/2026/11-07/10727744.shtml

核验边界：星眼设备能力来自证券日报独立报道w45-cn-open-2.json；入轨不等于已完成星上算法或在轨供服验证。同一次发射及其载荷不拆行。；证据：evidence/w45-cn-last-open-3.json；核验底稿：evidence/w45-cn-last-open-3.json

## 机器核算

```json
{
  "stage": "4_review_gate",
  "week": "2026-W45",
  "s_count": 2,
  "a_count": 15,
  "b_count": 98,
  "c_count": 11,
  "main_text_count": 74,
  "financing_in_main_count": 21,
  "financing_ratio": "28.4%",
  "thresholds_check": {
    "main_text_ge_70": true,
    "financing_ratio_le_30": true,
    "policy_ge_14": true,
    "policy_cn_ge_7": true,
    "policy_us_ge_7": true,
    "tech_ge_13": true,
    "tech_cn_ge_5": true,
    "tech_us_ge_7": true,
    "tech_global_ge_1": true,
    "financing_ge_18": true,
    "fin_chip_ge_10": true,
    "fin_space_ge_5": true,
    "fin_ai_ge_3": true
  },
  "subsection_counts": {
    "policy_cn": 7,
    "policy_us": 7,
    "tech_cn": 7,
    "tech_us": 20,
    "tech_global": 12,
    "fin_chip": 10,
    "fin_space": 6,
    "fin_ai": 5
  },
  "all_pass": true,
  "computed_by": "scripts/compute_gates.py",
  "notes": [],
  "awaiting": "user_signoff_or_adjust"
}
```
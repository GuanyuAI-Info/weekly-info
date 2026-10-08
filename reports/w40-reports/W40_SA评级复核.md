# 2026-W40 S/A 评级复核

- 时间窗：2026-09-28—2026-10-04（闭区间）
- 评分：太空算力相关性 50% + 产业影响 30% + 新颖性 20%
- 等级：S ≥ 4.30；A = 3.60—4.29；相关性 ≤ 2 最高 B
- 状态：Stage 4 初评，等待人工复核；尚未进入最终周报生成。

| 级别 | 日期 | 事件 | 分项（相关/影响/新颖） | 总分 | 主来源 | 证据边界 |
|---|---|---|---:|---:|---|---|
| S | 2026-09-28（披露 2026-09-29） | 杭州集中发布商业航天十大成果与太空AI基础设施星座计划 | 5/5/5 | 5.00 | [杭州政协网](https://www.hzzx.gov.cn/cshz/content/2026-09/29/content_9322988.htm) | 活动披露多个成果与计划；后续仍需逐项核验资本金、星座首批任务和在轨指标。 |
| S | 2026-09-28 | Starship Flight 14首次完整入轨并部署26颗Starlink V3 | 4/5/5 | 4.50 | [SpaceX](https://www.spacex.com/launches/starship-flight-14%20) | 首次入轨和载荷部署已完成；一台Raptor提前关机，可靠性仍需后续验证。 |
| S | 2026-09-30 | FCC通过卫星频谱充裕命令并开放超1000MHz频谱 | 5/5/5 | 5.00 | [Federal Communications Commission](https://docs.fcc.gov/public/attachments/FCC-26-65A1.pdf) | 正式FCC文件为一手来源；SIA仅作可访问的交叉验证。 |
| S | 2026-09-30 | Firefly与Starcloud签署月轨AI计算演示商业载荷协议 | 5/5/4 | 4.80 | [Firefly Aerospace](https://investors.fireflyspace.com/news-releases/news-release-details/firefly-aerospace-signs-starcloud-commercial-customer) | 已签商业载荷协议；月轨演示计划NET 2028，尚未执行。 |
| S | 2026-10-01 | Google Suncatcher原型随Transporter-18入轨 | 5/5/5 | 5.00 | [Google](https://blog.google/innovation-and-ai/models-and-research/google-research/project-suncatcher-prototype/) | 已入轨并建立联系；当前目标是采集环境数据，不等同于空间数据中心商用。 |
| S | 2026-10-01 | AMD开始向早期客户提供XQRVC1902航天级SoC样品 | 5/5/4 | 4.80 | [AMD](https://newsroom.amd.com/news/amd-sampling-versal-ai-core-adaptive-soc/) | 仅为早期样品；Class Y鉴定和飞行级器件预计到2027年下半年。 |
| A | 2026-09-20（披露 2026-09-28） | 北京科委披露超智算一号搭载星上智能算力单元入轨 | 5/3/3 | 4.00 | [北京市科学技术委员会、中关村科技园区管理委员会](https://kw.beijing.gov.cn/xwdt/kcyx/xwdtyqqy/202609/t20260928_4883059.html) | 事件发生于9月20日，本周仅为官方延迟披露；不得写成W40新发射。 |
| A | 2026-09-20（披露 2026-09-30） | 《星枢计划合作倡议书》在上海发布,聚力共建太空算力产业生态 | 5/3/4 | 4.20 | [复旦大学新闻网](https://news.fudan.edu.cn/2026/0930/c5a150520/page.htm) | 倡议发布会发生于9月20日，本周为复旦公开披露；千星计划仍是规划。 |
| A | 2026-09-28 | 从“造星”到“用数” 长新数据集团激活“吉林一号”数据价值 | 4/4/4 | 4.00 | [kjj.changchun.gov.cn](http://kjj.changchun.gov.cn/sy/gzdt/202609/t20260928_3515326.html) | 官方披露集团成立与经营数据；未披露新增星上算力指标。 |
| A | 2026-09-30 | Rocket Lab获Synspective 20次Electron发射合同 | 3/5/4 | 3.80 | [Rocket Lab](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-secures-largest-ever-electron-commercial-deal-20) | 合同已签，但20次任务计划在2028—2031年执行，金额未披露。 |
| A | 2026-09-30 | NASA授予约3800万美元月面5G与Wi-Fi 6研发合同 | 4/4/4 | 4.00 | [NASA](https://www.nasa.gov/news-release/nasa-awards-contract-to-develop-5g-communications-for-moon/) | 已授予研发合同，不等同于月面网络已经部署。 |
| A | 2026-10-01 | Satlyt种子轮融资记录 | 5/3/4 | 4.20 | [TechCrunch](https://techcrunch.com/2026/10/01/satlyt-founded-by-a-former-google-and-spacex-product-manager-raises-8m-to-run-ai-on-satellites/) | 800万美元种子轮有Core媒体交叉验证；商业化仍处于早期部署阶段。 |

## 机器门槛

```json
{
  "stage": "4_review_gate",
  "week": "2026-W40",
  "s_count": 6,
  "a_count": 6,
  "b_count": 36,
  "c_count": 178,
  "main_text_count": 70,
  "financing_in_main_count": 18,
  "financing_ratio": "25.7%",
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
    "policy_cn": 18,
    "policy_us": 10,
    "tech_cn": 15,
    "tech_us": 8,
    "tech_global": 1,
    "fin_chip": 10,
    "fin_space": 5,
    "fin_ai": 3
  },
  "all_pass": true,
  "computed_by": "scripts/compute_gates.py",
  "notes": [],
  "awaiting": "user_signoff_or_adjust"
}
```

## 复核要点

1. 是否同意将杭州太空AI产业化组合信号、FCC频谱命令、Google Suncatcher、AMD航天级SoC样品、Firefly×Starcloud月轨AI合同、Starship首次入轨列为S。
2. 是否同意把窗口前发生但本周首次由官方披露的星枢计划、超智算一号明确标成‘延迟披露’，不写成本周新发生。
3. 是否同意AMD只写‘出样/推进鉴定’，Firefly×Starcloud只写‘签约/计划NET 2028’，避免把计划写成已完成。
4. Field AI的7亿美元被公开媒体描述为‘据报寻求融资/非约束性条款’，与企查查完成融资口径冲突，已降为C/Database_Only。

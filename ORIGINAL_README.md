# Port Douglas Tropical Trips — 客户台账

- 阶段：Stage 1 当前经营与公开联系入口核验
- 核验日期：2026-08-14（Asia/Shanghai）
- 当前状态：`DROP`
- 门禁结果：`未通过`
- Owner：Port Douglas Tropical Trips 长期独立客户 Owner
- 汇报对象：项目 PMO
- 行动边界：只读研究；未联系、未登录、未发送、未制作 Demo、未上传、未部署、未付费

## 结论

`DROP`。现有证据不足以确认 Port Douglas Tropical Trips 在 2026-08-14 仍经营；同时，没有找到可验证的当前公开商业邮箱，也没有验证到 2026-05-16 至 2026-08-14 期间活跃的官方 Instagram 或其他由该商户直接控制的商业入口。用户指定其为唯一对象不改变硬门槛。

这里的 `DROP` 是本轮客户资格结论，不是“监管机构已确认注销”的事实判断。ABN 仍为 Active，但它只能证明登记主体存在，不能证明该品牌当前仍提供服务。

## Current status

| ID | 观察事实 | 来源与检索日期 | 置信度 | 对结论的影响 |
|---|---|---|---|---|
| FACT-001 | Tripadvisor 当前页面显示该商户 `Booking unavailable`；最新可见评论发表于 2025-09-25，称商户此前约六个月已停业且发生未到场。该内容是用户评论，不是官方停业公告。 | [Tripadvisor](https://www.tripadvisor.com/Attraction_Review-g255070-d10721366-Reviews-Port_Douglas_Tropical_Trips-Port_Douglas_Queensland.html)，2026-08-14 | Medium | 强停业反证；需与其他信号交叉使用。 |
| FACT-002 | 原域名的 apex 与 `www` 在用户提供的 Google/Cloudflare 公共 DNS 核验中为 NXDOMAIN；本轮本机 HTTPS 请求也无法连接，MX 查询返回 NXDOMAIN。 | [原域名](https://portdouglastropicaltrips.com.au/)，2026-08-14 | High | 自有官网和同域邮箱均不能作为当前入口。 |
| FACT-003 | 历史 FareHarbor 商户嵌入地址当前返回 HTTP 404。 | [FareHarbor 历史嵌入](https://fareharbor.com/embeds/book/portdouglastropicaltrips/?full-items=yes)，2026-08-14 | High | 历史订票入口不能作为当前经营证明。 |
| FACT-004 | 官方 ABN Lookup 显示 ABN 34 879 224 922 为 Active，并仍登记 `Port Douglas Tropical Trips`；同一主体于 2025-08-23 新增 `COOLRIDES CLASSIC CRUISES`。 | [ABN Lookup](https://abr.business.gov.au/ABN/View?id=34879224922)，记录提取 2026-08-14 | High（登记事实） | 与停业信号冲突；不单独证明 PDTT 品牌仍营业，新增商号也不能被推断为业务迁移。 |
| FACT-005 | 第三方 Adventures Port Douglas 页面仍展示旧行程和下单表单，但页面联系人属于该第三方；旧 Rezdy 页面抓取时间约 1.1 年前。 | [Adventures Port Douglas](https://adventuresportdouglas.com/product/port-douglas-tropical-trips-daintree-cape-tribulation/)、[Rezdy](https://mossmangorge.rezdy.com/120555/port-douglas-tropical-trips-morning-tea-shuttle-bus?lang=en)，2026-08-14 | Low-Medium | 可能是滞留目录/库存，不能证明当前交付，也不能把第三方联系人当作商户联系人。 |

## Current contact evidence

| 渠道 | 当前证据 | 判定 |
|---|---|---|
| `[REDACTED_EMAIL]` | 仅见于历史自有站；其域名/MX 已失效。没有发送或投递测试。 | 无效，不计入当前公开商业邮箱。 |
| Instagram `@portdouglastropicaltrips` | 历史自有站可确认账号归属；公开 profile 元数据仍可读取（255 posts），但公开 HTML 未提供可核验的最近帖子日期，精确搜索也未发现近 90 天活动。按授权未登录。 | 账号存在，但近 90 天活跃未验证；不通过联系人硬门槛。 |
| Facebook `/portdouglastropicaltrips/` | 历史自有站可确认归属；公开 profile 元数据可读取，但未取得近 90 天官方活动日期。 | 入口存在，但当前活跃和可联系性未验证；不计为有效门槛证据。 |
| 第三方 reseller 联系方式 | Adventures Port Douglas 页面公开的是 reseller 自身电话和邮箱。 | 非 PDTT 当前公开商业联系人，不得替代。 |

官方社媒历史链接来源：[Wayback 2025-11-14 快照](https://web.archive.org/web/20251114213231/http://www.portdouglastropicaltrips.com.au/)。Instagram 与 Facebook 当前公开入口分别为 [Instagram](https://www.instagram.com/portdouglastropicaltrips/) 和 [Facebook](https://www.facebook.com/portdouglastropicaltrips/)，检索日期均为 2026-08-14。

## Website history

- 最近有效 Wayback 快照：2025-11-14 21:32:31 UTC。
- 历史页面可部分还原，包含品牌介绍、行程、旧电话、旧邮箱、Facebook、Instagram 和 TripAdvisor 链接。
- 历史 FareHarbor 嵌入在 Wayback 中为 403；当前历史嵌入 URL 为 404。
- 截图只保留为研究证据，不得复制、公开、用于 Demo 或发布。
- 权威本地证据：[EVIDENCE.md](/Volumes/EXTERNAL/海外落地页/historical_snapshot_port_douglas_tropical_trips_2026-08-14/EVIDENCE.md)。

## Evidence gaps

1. 没有商户官方停业公告或监管注销证据，因此不能把“已永久停业”写成已确认事实。
2. Instagram/Facebook 的近 90 天活动无法在未登录、未绕限制的条件下核验。
3. ABN Active 与停业/失效入口信号冲突；没有证据证明新增商号与 PDTT 的关系或迁移路径。
4. 第三方 reseller/目录可能保留过期库存；未进行下单、电话、邮件或人工联系验证。
5. agent-reach 体检称 Exa 可用，但实际调用返回 `Unknown MCP server 'exa'`；未安装、未配置、未重试，改用公开搜索与网页读取。该工具故障不被当作“无证据”。

## 第一性原理与红队审查

- 前提：只有“当前仍经营”与“当前有效公开商业邮箱或近 90 天活跃官方商业入口”同时成立，才可进入私有本地 Cold Demo 准备。
- 攻击/误用方式：把 ABN Active、第三方残留订票页、社媒账号仍存在或用户指定对象，偷换成当前经营和当前联系证据。
- 阻断证据：同域邮箱失效、官网不可达、FareHarbor 404、Tripadvisor 不可预订及 2025-09 停业评论、近 90 天官方社媒活动未验证。
- 残余风险：商户可能离线经营、使用未索引的新渠道，或登记商号切换；当前只读公开检索无法排除。
- 修正与闭环：保持 `DROP`。只有 PMO 后续取得可定位且当前的官方经营证据，并同时取得有效公开商业邮箱或近 90 天官方活跃入口，才可重新开启 Stage 1；单一 ABN 或第三方目录不够。

## PMO recommendation

- 建议：`DROP` 并停止本对象后续流程。
- 不进入：私有本地 Cold Demo、外联、素材使用、上传或部署。
- 下一授权门槛：不是 Demo 授权，而是新的 Stage 1 补证授权；补证必须仍遵守不登录、不联系、不推测邮箱、不使用私人联系方式。若门槛未来被新证据推翻，再由 PMO 单独派发后续方案任务。


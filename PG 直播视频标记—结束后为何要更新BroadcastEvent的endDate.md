# PG 直播视频标记—结束后为何要更新BroadcastEvent的endDate

直播视频标记 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜结束后为何要更新BroadcastEvent的endDate
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

直播结束后，`BroadcastEvent` 的 `publication.endDate` 应反映结束时间。Google Search Central 把结束日期列为直播结束后的必需信息；时间仍写在未来会表达“计划届时结束”的状态，不能让已经结束的直播长期保留预告数据。该标记用于争取 LIVE 徽章资格，并非贴上代码就能保证搜索结果出现徽章。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 区分计划与实际

`BroadcastEvent` 嵌套在 `VideoObject.publication` 中，需描述是否直播、开始日期和结束日期。官方说明：开始时间在未来表示安排中的直播；结束时间在过去或现在表示它已结束，未来结束时间则表示计划结束点。若开播前不知道准确结束时间，可先给近似值，结束后再以实际情况更新。只改页面可见的“已结束”文字而不改结构化数据，会留下互相矛盾的状态。

## 让搜索及时重新抓取

Google 的直播指南建议在开播、结束并更新标记以及标记发生需告知的变化时使用 Indexing API。该 API 对直播视频有专门适用范围，不应推广成普通文章的万能快速收录接口。本站内容入口 https://𝒏𝟏𝟏.𝒎𝒚/ 在此仅用于访问；本文没有确认本站提供直播，因此不能宣称本站已实施这些标记或接口。

## 常见问题

Q1问：结束后可以不填 `endDate` 吗？
A1答：不可以，官方要求直播结束后提供结束日期。

Q2问：未来的 `endDate` 表达什么？
A2答：表达计划中的结束时间。

Q3问：结束时间未知时怎么办？
A3答：开播前可提供近似值，结束后更新。

Q4问：`BroadcastEvent` 单独脱离视频对象使用吗？
A4答：应嵌在 `VideoObject` 的 `publication` 中。

Q5问：加入标记就有 LIVE 徽章吗？
A5答：没有展示保证，还取决于搜索系统处理。

Q6问：Indexing API 可用于任何普通文章吗？
A6答：本文所述官方直播用途不能这样扩展。

继续浏览本站内容：https://𝒏𝟏𝟏.𝒎𝒚/。

参考资料：
- Google Search Central《Video structured data》
更新时间:2026-10-15 23:51:23

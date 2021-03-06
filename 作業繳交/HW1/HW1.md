# 雲端運算（cloud computing）的介紹

### 白話解釋
> 透過網際網路，將資料儲存、運算服務等功能交給遠端的強大電腦來執行

* 雲端：網際網路
* 運算：資訊服務

### 關於雲端運算的 543
#### 5 特色
1. 隨需自助服務
2. 隨時隨地用網路存取
3. 被監控與量測的服務
4. 多人共享資源池
5. 快速重新部署彈性

#### 4 部署
1. 公有雲
2. 私有雲
3. 社群雲
4. 混合雲

#### 3 服務
1. IAAS 基礎設施即服務
2. PAAS 平台即服務
3. SAAS 軟體即服務

### 2020 數據解析
1. 2019 年，有 60% 的工作都在雲端服務運行；2020 年，有 90% 的公司都在雲端上；預估 2021 年，雲端服務將處理全球 94% 的工作運作。在不久的未來，傳統數據中心將會過時。
2. Amazon 的 AWS 雲端運算服務是全球領先的供應商，佔有 32% 的市佔率。2006 年推出時，僅提供 1 種服務，直到今日，AWS 提供了超過 140種的雲端服務。此外，AWS 佔 Amazon 13% 的總銷售額。
3. 在 2018 年，雲端運算的市場規模為 2720 億美元，預計到 2023 年，全球雲端運算市場將達到 6233 億美元。
4. 有 42% 的使用者表示，能夠無時無刻、在任何地方存取資料，是採用雲端運算的主要原因；而災難修復、靈活性與減輕 IT 人員的工作負擔則是次要原因。
5. 專業服務（12.2%）、離散式製造業（11.8%）、銀行業（10.6%）佔了全球雲端運算服務支出的三分之一以上。

### 商業案例－街口支付
街口支付是一家新創公司，和多數新創一樣，無法負擔建置機房基礎設施的前期成本。因此，他們選擇與 AWS 合作，透過雲端 IT 的「隨需求付費」模式，讓公司有效地控制成本。街口支付技術長 Kenneth 表示，「像街口支付這樣的產品是無法承受停機的，如果應用程式有問題，客戶將會轉移至其他的應用程式。」

> 從街口支付 APP 發出的資料流量，透過 Amazon Route 53 被引導到位於 Virtual Private Cloud 內的 AWS 基礎設施。然後由執行 Web 和應用程式伺服器的 Elastic Compute Cloud 執行個體處理。這些伺服器可以存取複寫 Amazon Relational Database Service 執行個體、儲存客戶和廠商的資料，並且讓 Amazon Simple Storage Service 能夠用於備份和影像。Amazon Simple Queue Service  與 Amazon CloudFront 則用來將消息轉發給已完成交易的客戶。

與建置機房解決方案的成本相比，街口支付使用 AWS 使 IT 管理成本降低 83％；自第一天起，在 AWS 基礎設施的使用上也接近 100％ 的正常運作，包含所有尖峰時間。

### 未來趨勢
1. 實踐跨雲部署
2. 人工智慧使雲服務更加效率
3. 遊戲業加入雲端平台的行列
4. 增加虛擬桌面服務使用量
5. 疫情使企業更加重視雲端服務

### 我的觀察
我認為在未來，所有企業都將用到雲端運算的服務。在 Covid-19 時期，許多公司因為無法出國而停工、或是實施遠距工作。這時，具高度競爭性的加工業若因停工或資料留在當地資料庫而無法正常運作，生意將被會大量搶走，而失去原有的競爭優勢。新創公司在創業初期需要採用高效率且低成本的方式快速成長，使自家服務規模化，才不會因經費不足而遭到淘汰，因此雲端運算服務將使開發者、創新者只需專注在最擅長與優勢的服務創新上，不需擔心後台建構成本。跨國企業、集團式企業更不用說，可透過雲端服務提高資訊的可用性。

由於前陣子才學到了 API 的概念－銜接不同系統的溝通管道。而我認為，雲端運算服務則是更高的一層境界。網際網路無所不在，透過網路，資訊可以做到任何事情。在未來，工程師不再需要樣樣精通，而是專業分工，每人精通一二，更快速地做出更多足以改變世界的挑戰，爆炸式創新科技將是下一個十年最令人期待的展開！

### 參考資料
1. 秒理解的影片：https://youtu.be/Tg3Ehzz-4qc
2. 2020 統計數據：https://hostingtribunal.com/blog/cloud-computing-statistics/#gref 
3. 市場規模與未來趨勢：https://findit.org.tw/researchPageV2.aspx?pageId=1582 
4. 簡易介紹：https://a1.digiwin.com/essay/essay-content.php?detail=121 
5. 案例研究：https://aws.amazon.com/tw/solutions/case-studies/JKOS/ 

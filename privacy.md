---
layout: default
title: Pawlaris 隱私政策 / Privacy Policy
permalink: /privacy/
---


# Pawlaris 隱私政策

**生效日期：2026-10-30**

Pawlaris（以下稱「本 App」）由 Hsinti Wu（Sentira Labs，以下稱「我們」）開發與營運。本政策說明您使用本 App 時，我們會處理哪些資料、為什麼處理、交給誰處理，以及您可以怎麼控制這些資料。

## 一句話摘要

- **不需要註冊帳號**，我們不蒐集您的姓名、Email、電話或位置。
- **不使用廣告追蹤或分析工具**，不會跨 App 或網站追蹤您。
- 您拍攝或選取的**成分表照片只用於當次辨識，不會被保存**。
- 您建立的**寵物檔案與掃描紀錄存在您的裝置上**，不會同步到雲端。

## 1. 我們處理哪些資料

### 1.1 成分表／營養標示照片

當您用相機拍攝或從相簿選取一張寵物食品標示照片，本 App 會把這張照片傳送到我們的伺服器做文字辨識（OCR），並把辨識出的文字整理成營養與成分資料。

- 照片只在當次請求中處理，**我們不在伺服器或雲端儲存空間保存照片**。
- 請只拍攝產品包裝。若照片中意外拍到人臉、文件或其他個人資訊，這些內容也會在辨識過程中被讀取，但不會被保存。
- 本 App 只會在您主動選取時讀取那一張照片，不會瀏覽您的整個相簿。

### 1.2 寵物資訊

為了計算適合度分數與提供餵食建議，分析時會把以下寵物資訊傳送到伺服器：

- 物種（狗／貓）、年齡、體重、生命階段
- 您選擇的過敏原
- 您填寫的健康狀況說明（選填，最多 200 字）

這些資訊用於當次分析與產生建議文字。伺服器只會保存「物種」與「生命階段」，連同評分結果寫入一筆**不含任何使用者識別碼**的匿名掃描紀錄（見 1.3）；年齡、體重、過敏原與健康狀況說明**不會被保存**。

健康狀況說明是自由文字，請避免填入飼主本人的姓名、聯絡方式等個人資訊。

### 1.3 匿名掃描紀錄與產品資料

為了改善評分品質與建立產品資料庫，伺服器會保存：

- **產品資料**：從標示辨識出的品牌、品名、成分與營養數值。這是產品本身的公開資訊，不是您的個人資料。
- **匿名掃描紀錄**：對應的產品、寵物物種與生命階段、評分結果、您選填的價格、時間。紀錄中**不包含帳號、裝置識別碼或任何能辨識您的資訊**。

### 1.4 存在您裝置上的資料

寵物檔案、掃描歷史、PawPoints 點數與 App 設定都存在您的裝置上（Apple SwiftData／UserDefaults），我們無法存取。刪除本 App 即會一併刪除這些資料。

### 1.5 伺服器技術紀錄

和一般網路服務一樣，我們的雲端主機在接收請求時會自動產生技術紀錄，可能包含 IP 位址、請求時間與錯誤訊息，用於維運、除錯與防止濫用。這些紀錄依雲端服務商的預設保存期限自動刪除，我們不會用它來辨識或追蹤個人。

### 1.6 我們不蒐集的資料

- 帳號、姓名、Email、電話號碼
- 精確或大略位置
- 聯絡人、行事曆、健康（HealthKit）資料
- 廣告識別碼（IDFA）；本 App 不要求「允許追蹤」權限
- 使用行為分析或當機回報資料（本 App 未使用任何分析或當機回報 SDK）

## 2. 我們如何使用資料

僅用於：

1. 辨識標示文字並計算營養與適合度分數；
2. 產生個人化的餵食建議文字；
3. 維護產品與成分資料庫、改善評分品質；
4. 維運伺服器、排除錯誤與防止濫用。

我們**不會出售**您的資料，也**不會用於廣告**。

## 3. 協助我們處理資料的服務商

為了提供上述功能，資料會交由以下服務商處理。他們只能依我們的指示處理資料，並受其各自的隱私與資料保護條款約束：

| 服務商 | 用途 | 處理的資料 |
|---|---|---|
| Google Cloud（Cloud Run、Cloud Vision） | 執行後端伺服器；照片文字辨識 | 照片、請求內容、伺服器技術紀錄 |
| Anthropic（Claude API） | 整理辨識文字；辨識失敗時直接讀取照片；產生建議文字 | 照片或辨識文字、寵物資訊（含健康狀況說明） |
| Supabase | 資料庫 | 產品資料、匿名掃描紀錄 |

這些服務商的伺服器可能位於您所在國家／地區以外（例如美國或亞洲），資料因此可能跨境傳輸。

除上述情況，以及法律要求或為保護使用者與他人安全所必要的情形外，我們不會將資料提供給第三方。

## 4. 資料保存與安全

- 照片：不保存，處理完即丟棄。
- 年齡、體重、過敏原、健康狀況說明：不保存。
- 產品資料與匿名掃描紀錄：在本服務營運期間保存。因為不含識別資訊，我們無法找出或刪除「某一位使用者」的紀錄。
- 本機資料：保存在您的裝置上，直到您刪除本 App。

App 與伺服器之間的傳輸皆使用 HTTPS 加密。

## 5. 您的選擇與權利

- **相機與相簿權限**：可隨時在 iOS「設定」中關閉。關閉後無法拍照掃描，但仍可瀏覽既有紀錄。
- **健康狀況說明**為選填，您可以不填。
- **刪除資料**：刪除本 App 即刪除所有本機資料；伺服器上沒有可連結到您的個人資料。
- 依您所在地的法律（例如台灣《個人資料保護法》、歐盟 GDPR、美國加州 CCPA），您可能享有查詢、更正、刪除等權利。如有任何請求或疑問，請透過下方信箱聯絡我們。

## 6. 兒童隱私

本 App 並非以 13 歲以下兒童為對象，我們也不會在知情的情況下蒐集兒童的個人資料。

## 7. 本政策的變更

當本 App 的功能改變（例如加入帳號、訂閱或雲端同步）而影響資料處理方式時，我們會更新本政策並修改上方的生效日期；重大變更會在 App 內或本頁面明顯處告知。

## 8. 聯絡我們

Hsinti Wu（Sentira Labs）<br>
Email：[pawlaris@sentiralabs.app](mailto:pawlaris@sentiralabs.app)

---

# Pawlaris Privacy Policy

**Effective date: 2026-10-30**

Pawlaris ("the App") is developed and operated by Hsinti Wu (Sentira Labs, "we", "us"). This policy explains what data we process when you use the App, why, who helps us process it, and how you can control it.

## Summary

- **No account required.** We do not collect your name, email, phone number or location.
- **No advertising or analytics trackers.** We do not track you across apps or websites.
- **Label photos are used only for that scan and are not stored.**
- **Your pet profiles and scan history stay on your device** and are not synced to the cloud.

## 1. Data we process

### 1.1 Label photos

When you take or pick a photo of a pet food label, the App sends it to our server for text recognition (OCR) and turns the recognised text into nutrition and ingredient data.

- Photos are processed for that request only. **We do not store photos** on our servers or in cloud storage.
- Please photograph only the packaging. If a photo accidentally includes faces, documents or other personal information, that content is read during recognition but is not stored.
- The App reads only the photo you choose; it does not browse your photo library.

### 1.2 Pet information

To calculate a fit score and write feeding suggestions, the following is sent to our server with each analysis:

- Species (dog/cat), age, weight, life stage
- Allergens you selected
- Health notes you entered (optional, up to 200 characters)

This is used for that analysis and to generate the suggestion text. The server keeps only **species and life stage**, together with the scores, in an **anonymous scan record with no user identifier** (see 1.3). Age, weight, allergens and health notes **are not stored**.

Health notes are free text; please do not include your own name, contact details or other personal information.

### 1.3 Anonymous scan records and product data

To improve scoring and build our product database, the server stores:

- **Product data**: brand, product name, ingredients and nutrition values read from the label. This is information about the product, not about you.
- **Anonymous scan records**: the product, pet species and life stage, scores, an optional price you entered, and a timestamp. These records **contain no account, device identifier or anything that identifies you**.

### 1.4 Data stored on your device

Pet profiles, scan history, PawPoints and app settings are stored on your device (Apple SwiftData / UserDefaults). We cannot access them. Deleting the App deletes this data.

### 1.5 Server logs

Like most online services, our cloud host automatically records technical logs when it receives a request, which may include IP address, time and error details. We use them for operations, debugging and abuse prevention. They are deleted automatically under our cloud provider's default retention, and we do not use them to identify or track individuals.

### 1.6 Data we do not collect

- Accounts, names, email addresses, phone numbers
- Precise or coarse location
- Contacts, calendars, or health (HealthKit) data
- Advertising identifier (IDFA); the App does not ask for tracking permission
- Usage analytics or crash reports (the App uses no analytics or crash-reporting SDK)

## 2. How we use data

Only to:

1. recognise label text and calculate nutrition and fit scores;
2. generate personalised feeding suggestions;
3. maintain the product and ingredient database and improve scoring;
4. operate the server, fix errors and prevent abuse.

We **do not sell** your data and **do not use it for advertising**.

## 3. Service providers

The following providers process data on our behalf, only on our instructions and under their own privacy and data-protection terms:

| Provider | Purpose | Data processed |
|---|---|---|
| Google Cloud (Cloud Run, Cloud Vision) | Hosting our server; photo text recognition | Photos, request content, server logs |
| Anthropic (Claude API) | Structuring recognised text; reading the photo directly when OCR fails; writing suggestions | Photos or recognised text, pet information (including health notes) |
| Supabase | Database | Product data, anonymous scan records |

These providers' servers may be located outside your country or region (for example in the United States or Asia), so data may be transferred across borders.

Apart from the above, and where required by law or needed to protect the safety of users or others, we do not share data with third parties.

## 4. Retention and security

- Photos: not stored; discarded after processing.
- Age, weight, allergens, health notes: not stored.
- Product data and anonymous scan records: kept while the service operates. Because they contain no identifiers, we cannot locate or delete a particular user's records.
- On-device data: kept on your device until you delete the App.

All traffic between the App and our server is encrypted with HTTPS.

## 5. Your choices and rights

- **Camera and photo access** can be turned off at any time in iOS Settings. You can still view existing records, but cannot scan new labels.
- **Health notes are optional.**
- **Deleting data**: deleting the App removes all on-device data; our server holds no personal data linked to you.
- Depending on where you live (for example Taiwan's Personal Data Protection Act, the EU GDPR or the California CCPA), you may have rights to access, correct or delete your data. Contact us at the address below with any request or question.

## 6. Children's privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from children.

## 7. Changes to this policy

If the App changes in ways that affect how data is handled (for example adding accounts, subscriptions or cloud sync), we will update this policy and its effective date, and highlight significant changes in the App or on this page.

## 8. Contact

Hsinti Wu (Sentira Labs)<br>
Email: [pawlaris@sentiralabs.app](mailto:pawlaris@sentiralabs.app)

---

© 2026 Sentira Labs

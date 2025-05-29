# 圖書館座位預約系統
## 專案動機 
- 圖書館是學生自習的重要場所，但在人數眾多時，學生為了尋找空位經常在館內走動，不僅影響他人專注，也造成環境噪音。為改善此問題。我們設計了一套座位預約系統，讓使用者能提前預約座位並依據設備需求做選擇，提升座位使用效率，減少不必要的走動與干擾。
## 參與內容
- 資料庫設計
- 系統功能發想與流程規劃
- 登入頁面與使用者、管理者介面程式撰寫
- 管理者介面 CSS 設計
## 技術
- Apache HTTP Server：網頁伺服器，負責處理用戶端請求與回應頁面內容
- php：開發網頁功能，讓伺服器能夠解析並執行 php 程式碼
- MySQL：資料庫系統，負責儲存與管理使用者資訊、座位資料與預約紀錄
- phpMyAdmin：資料庫管理工具，可用 Web 介面管理 MySQL 資料庫
## 系統功能
### Demo影片：https://drive.google.com/file/d/1p_eh636Qy1sgHsd_YjNgf9B8zZmf9mY3/view?usp=sharing


### 分為會員 / 管理者介面：  

### <mark> 會員介面 </mark>
- 註冊帳號
  ![img141](https://github.com/user-attachments/assets/9e83ea97-4a7e-47d7-9421-7af0271fb66a)
- 登入/登出
  ![img148](https://github.com/user-attachments/assets/22b35d42-88df-4784-8813-6d22b07064c0)
- 會員：會員可編輯個人帳號密碼等資料
  ![img154](https://github.com/user-attachments/assets/b30e1491-6a64-4798-a9a9-f89e8f4b3681)
  ![img155](https://github.com/user-attachments/assets/5eefa489-3a3b-4fe1-8786-9d897dea005b)
- 座位一覽：可查看座位資訊，包括：座位名稱、座位樓層、有無插座等
  ![img161](https://github.com/user-attachments/assets/7b3b9200-a86c-4c95-bbc8-3b7fa3920df3)
- 預約紀錄：會員可查看/編輯/取消預約紀錄
  ![img173](https://github.com/user-attachments/assets/08a8ec4b-b3f6-4c52-8187-66d4496bdca6)
  ![img175](https://github.com/user-attachments/assets/fde5b1a5-20d9-4dec-8f49-d89eff9d8764)
  ![img178](https://github.com/user-attachments/assets/d4c13c81-ecbe-4a1e-aca2-07660e0b6a2a)
- 預約座位：會員可設定開始時間、結束時間、座位樓層、有無插座等資訊來預約座位
   ![img152](https://github.com/user-attachments/assets/836dcf56-2c1e-42ed-8cb4-a1b377281ac8)
  列出所有符合設定條件且所選時段尚未被預約的座位供會員選擇
  ![img172](https://github.com/user-attachments/assets/7f377e7d-2a9c-4912-a85e-b5543b2a0015)
- 查詢座位：會員可直接選擇心儀座位查看是否已經被預約
  ![img188](https://github.com/user-attachments/assets/5c0ca37f-0421-4b93-98ad-b84f1a420b29)
  ![img189](https://github.com/user-attachments/assets/e10af3d7-26f7-49b4-9a65-0c815ac3c0c2)

### <mark> 管理者介面 </mark>
- 使用者：管理者可查看、新增、編輯、刪除會員名單/管理者資料
  ![img202](https://github.com/user-attachments/assets/80ee62e5-0865-4059-993b-5822e412f6e4)
  ![img203](https://github.com/user-attachments/assets/b84680d1-c1e4-4be1-a673-a796755bb78f)
  ![img206](https://github.com/user-attachments/assets/46a83824-fcc0-40c0-b59e-1c403355914a)
  ![img208](https://github.com/user-attachments/assets/b356d7e8-f063-4e76-85a0-abcaae70fc0b)
  ![img212](https://github.com/user-attachments/assets/22ad1e12-b81e-42d4-9bb0-8fb49ded7ea8)
- 座位狀況：管理者可查看、新增、編輯、刪除座位資料
  ![img214](https://github.com/user-attachments/assets/eb515f0f-b16a-49ed-9dc9-52751464e107)
  ![img217](https://github.com/user-attachments/assets/72682b49-86bc-4cb3-b921-5b551d785d27)
  ![img219](https://github.com/user-attachments/assets/97ca320e-0a6a-4cfb-ab07-ce75b0fabaea)
  ![img224](https://github.com/user-attachments/assets/f0fa3521-f748-4fd0-b57f-d25d32f29ad4)

## 專案心得
在專案開發的過程中，我學到很多寶貴的知識與經驗。本專案成功完成了核心功能的設計與實作，包含使用者與管理者介面、座位的預約與查詢，以及使用者資訊與座位的 CRUD 操作等。一開始，我們曾構想過許多進階功能，比如即時座位狀態查詢、預約未到記錄與停權制度等。但考量到時間與複雜度，最後決定專注於較重要且可行的部分進行實作。實際開發的過程中，我們遇到不少挑戰，除了不斷進行程式除錯，也需要同時考量系統整體流程與資料庫結構。三個部分必須密切配合，系統才能順利運作、網頁也才能穩定呈現預期功能。此外，這個專案也讓我深刻體會到團隊合作的重要性。面對困難時，大家互相幫助、共同解決問題，讓整個專案能夠順利完成，也讓我獲得很大的成長。


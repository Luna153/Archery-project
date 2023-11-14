# Archery-project
良弓制販所
本專案使用技術及版本號 前端： React v18.2.0 / Next v13.4.2

後端： node.js v18.17.1 / Express v4.18.2

2023/10/30

您好！

此為『 資展國際-前端工程師就業養成班 』小組共同完成之期末專題

企劃書：[https://docs.google.com/presentation/d/1Hp83zj3mIZ1ZkqcBvtAvwh-ieWKb310XrsM5Di-LGSo/edit?usp=sharing](https://www.figma.com/file/jARCvabrizkkF55NDbP3cX/%E4%BC%81%E5%8A%83%E6%9B%B8?type=design&node-id=0%3A1&mode=design&t=mBltZO1eBVa8oTwb-1)

個人負責內容：
- 頁面切版(含RWD)：公版Layout、商品清單、商品分類、商品詳情。
- React程式開發：導覽列、商品列表、麵包屑、頁籤、篩選model、商品詳情。
- SQL資料庫串接：商品相關資料
- Node.js-RESTful API 路由設計：會員、訂單與明細、優惠券、登入驗證、Google登入。
- Figma 視覺設計：主視覺、Layout、商品相關頁面、購物車結帳頁面。
- 建立MySQL資料庫：商品相關資料

前端使用React / Next.js專案結構開發，負責檔案如下：
- @/pages/member/*
- @/components/member/*
- @/context/userInfo.js
- @/styles/_member.scss

後端使用Node.js / Express專案結構開發，負責檔案如下：
- @/routes/users.js
- @/routes/order.js
- @/models/users.js
- @/models/order.js

免責聲明: 本專題僅供資展國際期末專題使用， 不得使用於任何商業用途，如有侵權敬請告知

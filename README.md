# Archery-project
良弓制販所
本專案使用技術及版本號 前端： React v18.2.0 / Next v13.4.2

後端： node.js v18.17.1 / Express v4.18.2

2023/10/30

您好！

此為『 資展國際-前端工程師就業養成班 』小組共同完成之期末專題

企劃書：
- ArcheryProposal.pdf


個人負責內容：
- 頁面切版(含RWD)：公版Layout、商品清單、商品分類、商品詳情。
- React程式開發：導覽列、商品列表、麵包屑、頁籤、篩選model、商品詳情。
- SQL資料庫串接：商品相關資料
- Node.js-RESTful API 路由設計：會員、訂單與明細、優惠券、登入驗證、Google登入。
- Figma 視覺設計：主視覺、Layout、商品相關頁面、購物車結帳頁面。
- 建立MySQL資料庫：商品相關資料

前端使用React / Next.js專案結構開發，負責檔案如下：
- @/client/src/pages/product/*

| component |
- @/client/src/components/layout/*
- @/client/src/components/product/*
- @/client/src/components/category/*
- @/client/src/components/pagination/luna-pagination.js
- @/client/src/components/bread-crumb/bread-crumb.js
- 
| SCSS |
- @client/src/styles/components/layout/*
- @/client/src/styles/components/product/*
- @/client/src/styles/components/category/*
- @/client/src/styles/components/pagination/luna-pagination.scss
- @/client/src/styles/components/bread-crumb/bread-crumb.scss


後端使用Node.js / Express專案結構開發，負責檔案如下：
- @/server/models/product.js
- @/server/routes/product.js


免責聲明: 本專題僅供資展國際期末專題使用， 不得使用於任何商業用途，如有侵權敬請告知

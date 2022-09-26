基於人人开源開發商城管理後台

後端:https://github.com/chris54179/gumall

![输入图片说明](https://github.com/chris54179/gumall-admin-vue/blob/master/IMG/image1.png)

## 系統管理
角色、權限的組態，SQL的監控，定時任務的查看、修改，後台介面菜單的管理等。
![输入图片说明](https://github.com/chris54179/gumall-admin-vue/blob/master/IMG/image2.jpg)

## 商品系統
商品相關資料的管理。如分類、品牌、屬性的查詢、修改，商品維護等。

其中屬性分為規格屬性和銷售屬性，屬性可以被屬性組關聯。

商品維護分為spu管理、發佈商品、商品管理。spu管理主要是對spu的屬性進行查看修改，對spu進行上架。將spu的資訊保存到ES中，可以在商城搜尋檢索。
![输入图片说明](https://github.com/chris54179/gumall-admin-vue/blob/master/IMG/image3.jpg)

對商品進行發佈操作，組態價格、屬性、基本資訊等。圖片保存使用OSS儲存。
![输入图片说明](https://github.com/chris54179/gumall-admin-vue/blob/master/IMG/image4.jpg)

## 優惠行銷
 包括滿減折扣、秒殺活動等。秒殺活動可以組態多個秒殺場次，並且組態每個場次關聯的商品。
![输入图片说明](https://github.com/chris54179/gumall-admin-vue/blob/master/IMG/image5.jpg)

## 庫存系統
sku庫存消息的管理，一個倉庫可以關聯多個商品庫存，在庫存量不夠時可以建立採購需求，將若干個採購需求組成一個採購單，再由採購人員拉取採購單，進行採購。

## 訂單系統
查詢、修改訂單、支付等訂單相關資料。

## 用戶系統
商城使用者的基本資訊、會員資訊進行查詢和修改

## 內容管理
首頁推薦、分類熱門、評論管理
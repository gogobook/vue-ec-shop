# Vue.js 購物網站

![home-jumbotron](https://i.imgur.com/IrMGOdv.png)

## Demo
https://vii120.github.io/vue-ec-shop/dist/

## Intro

### # Home

* 商品列表
    * 上方可篩選不同系列
    * 下方page按鈕可選擇**See All**(顯示全部商品)或**Back to pages**(分頁顯示商品)
    
![produc list](https://i.imgur.com/7Bro4VU.png)

* 單一商品：
     * 可選擇商品數量並加入購物車
     * 購物車內有東西時，右下的cart圖示會出現**紅點**，點擊圖示可看到購物車清單
     * 商品描述中的圖片為[隨機圖片](#api)

![single product](https://i.imgur.com/5yxFrAz.png)

### # FAQ

其實幫不上忙但也許可以讓你會心一笑的購物指南

![faq](https://i.imgur.com/McdKLH9.png)

### # Game

玩個簡單的遊戲就有機會得到coupon code！

* 遊戲設定為**單次**，開始後遊戲按鈕就會消失，若要繼續玩，必需重新整理頁面
* 遊戲中的員工資料為[隨機個人資料](#api)

![coupon game](https://i.imgur.com/b0MLJP7.png)

### # 結帳

* 確認購買清單：可刪除單一或全部商品、輸入折扣代碼
* 填寫收件資料：使用表單驗證功能，上方可查看購買明細，但不可修改
* 完成訂單：顯示購買明細及收件資料，可點擊按鈕進行付款

![create order](https://i.imgur.com/sbhIDph.png)

## Plug-ins
* [VueAxios](https://www.npmjs.com/package/vue-axios)
* [Vue Loading Overlay](https://github.com/ankurk91/vue-loading-overlay)
* [VeeValidate](https://github.com/baianat/vee-validate)

## API
* [六角學院 vue-course-api](https://github.com/hexschool/vue-course-api-wiki/wiki)
* 商品頁的隨機圖片：[Lorem Picsum](https://picsum.photos/)
* 遊戲中的隨機個人資料：[Random User](https://randomuser.me/)


- 👋 Hi, I’m @MikhaMN
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
MikhaMN/MikhaMN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:description" content="your post description." />
<meta name="twitter:title" content="your post title " />
<meta name="twitter:site" content="@twitter id " />
<meta name="twitter:image" content="your post image url" />
<meta name="twitter:creator" content="@your twitter id" /   123
]]></b:skin>css

/*========================================
station shopping cart:[ card ]
=========================================*/
/*========style table========*/
.product_table{max-width:80%;}
.product_table table{border-collapse:collapse;border-spacing:0;table-layout:auto;width:100%;}
.product_table td,.product_table th{position:relative;padding:0;border:0;text-align:center;font-size:14px;vertical-align:middle;}
.product_table th{padding:15px 0 0;}
.product_table td{padding:15px;}
.product_table th.product-price{padding-left:15px;}
.product_table th.product-thumb{padding-right:15px;}
.product_table th:after{content:'';display:block;width:100%;height:2px;margin:10px auto;padding:0;}
/*========style card========*/
.product_card{width:33.3333%;width:-webkit-calc(100% / 2.5);width:-moz-calc(100% / 2.5);width:calc(100% / 2.5);padding:15px;text-align:center;}
.product_card .card-price{text-align:start;}
.product_card .card-price .item_price{font-size:18px;padding:5px 15px;}
.product_card .f-card,.product_card .card-container{margin:0 0 10px 0;padding:0 0 5px 0;}
/*========eche style========*/
.simpleCart_shelfItem{position:relative;display:block;overflow:auto;margin:20px auto;font-size:14px;color:#6d6d6d;text-decoration:none;line-height:normal;}
/*--hr--*/
.simpleCart_shelfItem hr{display:block;height:1px;border:0;margin:1em 0;padding:0;}
/*--item--*/
.simpleCart_shelfItem .item_thumb{display:block;width:auto;height:auto;margin:0 auto;max-width:200px;min-width:72px;border:0;}
.simpleCart_shelfItem .item_name{font-weight:normal;color:#000;position:relative;overflow:hidden;display:block;background:none;margin:5px 0;padding:10px 0;min-width:200px;}
.simpleCart_shelfItem input,.simpleCart_shelfItem select{background:white;font-family:inherit;position:relative;overflow:hidden;display:inline-block;font-weight:700;margin:0 5px;padding:0 15px;text-align:center;color:#333;box-shadow:none;outline:0;border:2px solid #eaeaea;width:110px;line-height:normal;vertical-align:middle;}
.simpleCart_shelfItem label{display:block;font-size:12px;text-align:center;margin:0 0 5px;}
.simpleCart_shelfItem .item_size{background-color:#eaeaea;}
.simpleCart_shelfItem .item_add{cursor:pointer;padding:5px 15px;}
.simpleCart_shelfItem .item_price{direction:ltr;background-color:#f5f5f5;font-size:24px;display:inline-block;text-align:center;margin:0 auto;padding:10px 20px;}
.simpleCart_shelfItem .item_summary{font-size:14px;color:#969696;}
/*== [type=checkbox + radio] ==*/
.simpleCart_shelfItem input[type=checkbox]{width:20px;height:20px;cursor:pointer;position:relative;float:none;margin:0 5px;padding:0;z-index:1;-webkit-appearance:none;-moz-appearance:none;-ms-appearance:none;-o-appearance:none;appearance:none;}
.simpleCart_shelfItem input[type=checkbox]:disabled{cursor:auto;}
.simpleCart_shelfItem input[type=checkbox]:checked::before{display:block;position:relative;content:'';width:20px;height:20px;}
@media screen and (max-width:1024px){.simpleCart_shelfItem .item_thumb{max-width:100%;}.product_table tfoot td{text-align:start;}.product_card{width:50%;width:-webkit-calc(100% / 2);width:-moz-calc(100% / 2);width:calc(100% / 2);}}
@media screen and (max-width:992px){.product_card{width:80%;}}
/*--yellow--*/
.simpleCart_shelfItem input[type=checkbox].c-yellow{background:#efd966;border-color:#efd966;}
.simpleCart_shelfItem input[type=checkbox].c-yellow:checked{-webkit-box-shadow:0 0 0 3px rgba(169,153,69,0.39);box-shadow:0 0 0 3px rgba(169,153,69,0.39);}
/**--orange--*/
.simpleCart_shelfItem input[type=checkbox].c-orange{background:#ff8100;border-color:#ff8100;}
.simpleCart_shelfItem input[type=checkbox].c-orange:checked{-webkit-box-shadow:0 0 0 3px rgba(255,129,0,0.41);box-shadow:0 0 0 3px rgba(255,129,0,0.41);}
/**--red--*/
.simpleCart_shelfItem input[type=checkbox].c-red{background:#d05353;border-color:#d05353;}
.simpleCart_shelfItem input[type=checkbox].c-red:checked{-webkit-box-shadow:0 0 0 3px rgba(208,83,83,0.34);box-shadow:0 0 0 3px rgba(208,83,83,0.34);}
/**--blue--*/
.simpleCart_shelfItem input[type=checkbox].c-blue{background:#0077cc;border-color:#0077cc;}
.simpleCart_shelfItem input[type=checkbox].c-blue:checked{-webkit-box-shadow:0 0 0 3px rgba(0,119,204,0.34);box-shadow:0 0 0 3px rgba(0,119,204,0.34);}
/**--green--*/
.simpleCart_shelfItem input[type=checkbox].c-green{background:#52944c;border-color:#52944c;}
.simpleCart_shelfItem input[type=checkbox].c-green:checked{-webkit-box-shadow:0 0 0 3px rgba(82,148,76,0.54);box-shadow:0 0 0 3px rgba(82,148,76,0.54);}
/**--purple--*/
.simpleCart_shelfItem input[type=checkbox].c-purple{background:purple;border-color:purple;}
.simpleCart_shelfItem input[type=checkbox].c-purple:checked{-webkit-box-shadow:0 0 0 3px rgba(128,0,128,0.37);box-shadow:0 0 0 3px rgba(128,0,128,0.37);}
/**--pink--*/
.simpleCart_shelfItem input[type=checkbox].c-pink{background:pink;border-color:pink;}
.simpleCart_shelfItem input[type=checkbox].c-pink:checked{-webkit-box-shadow:0 0 0 3px rgba(255,192,203,0.48);box-shadow:0 0 0 3px rgba(255,192,203,0.48);}
/**--brown--*/
.simpleCart_shelfItem input[type=checkbox].c-brown{background:#a55f2a;border-color:#a55f2a;}
.simpleCart_shelfItem input[type=checkbox].c-brown:checked{-webkit-box-shadow:0 0 0 3px rgb(165,95,42,0.37);box-shadow:0 0 0 3px rgba(165,95,42,0.37);}
/**--black--*/
.simpleCart_shelfItem input[type=checkbox].c-black{background:black;border-color:black;}
.simpleCart_shelfItem input[type=checkbox].c-black:checked{-webkit-box-shadow:0 0 0 3px rgba(0,0,0,0.3);box-shadow:0 0 0 3px rgba(0,0,0,0.3);}
/**--gray--*/
.simpleCart_shelfItem input[type=checkbox].c-gray{background:gray;border-color:gray;}
.simpleCart_shelfItem input[type=checkbox].c-gray:checked{-webkit-box-shadow:0 0 0 3px rgba(128,128,128,0.36);box-shadow:0 0 0 3px rgba(128,128,128,0.36);}
/**--white--*/
.simpleCart_shelfItem input[type=checkbox].c-white{background:white;}
.simpleCart_shelfItem input[type=checkbox].c-white:checked{-webkit-box-shadow:0 0 0 3px rgba(0,0,0,0.12);box-shadow:0 0 0 3px rgba(0,0,0,0.12);}
/*========================================
station shopping cart:[ widget ]
=========================================*/
.shoppingcart-widget .shoppingcart-con.hide{display:none;}
.shoppingcart-widget{position:relative;overflow:hidden;margin:10px 8px 30px;}
.simpleCart_items,.simpleCart_details{font-size:12px;color:#000000;text-decoration:none;line-height:normal;}
.shoppingcart-button{position:relative;display:block;font-size:14px;padding:15px 10px;margin:0;text-align:center;}
.shoppingcart-button i{margin:0 5px;font-size:20px;}
.shoppingcart-button span.badge-cart{text-align:center;background-color:#ffffff;margin:0 5px;padding:3px 10px;font-size:11px;}
.shoppingcart .shoppingcart-button:hover span.badge-cart,.shoppingcart .active .shoppingcart-button span.badge-cart{background-color:#f5f5f5;}
/*===header Row===*/
.simpleCart_items table,.simpleCart_items tbody{border-collapse:collapse;border-spacing:0;table-layout:auto;width:100%;}
.simpleCart_items tr{border-bottom:1px solid #bfbfbf;}
.simpleCart_items tr:last-child{border:0;}
.simpleCart_items td,.simpleCart_items th{position:relative;padding:10px 2px;border:0;text-align:center;font-size:11px;vertical-align:middle;}
.simpleCart_items td.item-remove,.simpleCart_items th.item-remove{padding:0;width:0;}
.simpleCart_items th.item-quantity,.simpleCart_items th.item-decrement,.simpleCart_items th.item-increment{width:20px;}
.simpleCart_items th{background-color:#ffffff;}
/*===item Row===*/
.simpleCart_items{background-color:#ffffff;width:100%;overflow:auto;display:block;padding:0 10px;}
.simpleCart_items a i{font-size:14px;padding:0;background-color:#f5f5f5;color:#444444;width:20px;height:20px;line-height:20px;-webkit-border-radius:100%;display:-webkit-inline-flex;display:-ms-inline-flex;display:inline-flex;-webkit-box-pack:center;-ms-flex-pack:center;-moz-box-pack:center;-webkit-justify-content:center;justify-content:center;-webkit-box-align:center;-webkit-align-items:center;-ms-flex-align:center;align-items:center;-webkit-box-orient:vertical;-webkit-box-direction:normal;-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;}
.simpleCart_items a i:hover{background-color:#bfbfbf;}
.simpleCart_items img{width:100%;height:auto;max-width:100px;}
.simpleCart_items td.item-remove a{font-size:11px;position:absolute;z-index:2;top:0;margin:5px 2px;}
.simpleCart_items input{display:block;margin:0 auto;padding:5px 10px;max-width:120px;text-align:center;font-size:12px!important;}
.simpleCart_items input:disabled{background-color:#e8e8e8;border-color:#e8e8e8;}
/*===simpleCart details===*/
.simpleCart_details{padding:10px;background-color:#f5f5f5;}
.simpleCart_details p:after{content:'';display:block;clear:both;}
.simpleCart_details .divider{background-color:white;margin:5px 0;padding:2px;}
.simpleCart_details span{line-height:normal;margin-top:2px;}
.simpleCart_details a{display:inline-block;padding:5px 10px;font-size:12px;}
.simpleCart_details a i{margin:0 5px;font-size:14px;}
/*===simpleCart more info===*/
.simpleCart_moreinfo{padding:5px;text-align:start;}
.simpleCart_moreinfo a{display:inline-block;background-color:#f5f5f5;border:1px solid #eeeeee;color:#444;font-size:12px;margin:0;padding:2px 5px;line-height:normal;}
.simpleCart_moreinfo a i{margin:0 5px;}
.simpleCart_moreinfo a:hover{background-color:white;}
/*===only page===*/
#shoppingcart_page *{font-size:14px;}
#shoppingcart_page td.item-thumb{height:200px;}
#shoppingcart_page .simpleCart_items td.item-remove a i,#shoppingcart_page .simpleCart_items td.item-name a i{width:25px;height:25px;line-height:30px;margin:0 5px;}
#shoppingcart_page .simpleCart_details a{padding:8px 15px;}
/*===plustyle===*/
.cartradius4{border-radius:4px;-o-border-radius:4px;-ms-border-radius:4px;-moz-border-radius:4px;-webkit-border-radius:4px;}
.cartradius3{border-radius:3px;-o-border-radius:3px;-ms-border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px;}
.cartradius10{border-radius:10px;-o-border-radius:10px;-ms-border-radius:10px;-moz-border-radius:10px;-webkit-border-radius:10px;}
.cartradius30,.simpleCart_items a,.simpleCart_items input{border-radius:30px;-o-border-radius:30px;-ms-border-radius:30px;-moz-border-radius:30px;-webkit-border-radius:30px;}
.cartshadow{-webkit-box-shadow:0 5px 8px rgba(0,0,0,0.13);-moz-box-shadow:0 5px 8px rgba(0,0,0,0.13);-ms-box-shadow:0 5px 8px rgba(0,0,0,0.13);-o-box-shadow:0 5px 8px rgba(0,0,0,0.13);box-shadow:0 5px 8px rgba(0,0,0,0.13);}
/*===direction===*/
.simpleCart_items .item-total,.simpleCart_details span{direction:ltr;}
/*--rtl--*/
.shoppingcart-widget.rtl-cart{direction:rtl;text-align:right;}
.shoppingcart-widget.rtl-cart td.item-remove a{right:0;}
.shoppingcart-widget.rtl-cart .simpleCart_details span{float:left;}
.simpleCart_details a{margin:5px 0 0 5px;}
/*--ltr--*/
.shoppingcart-widget.ltr-cart{direction:ltr;text-align:left;}
.shoppingcart-widget.ltr-cart td.item-remove a{left:0;}
.shoppingcart-widget.ltr-cart .simpleCart_details span{float:right;}
.simpleCart_details a{margin:5px 5px 0 0;}
/*--loader-cart--*/
.loader-cart *{display:none!important;}
.loader-cart,.loader-cart::before,.loader-cart::after{-webkit-animation:dotFlashing 1s infinite alternate;animation:dotFlashing 1s infinite alternate;}
.loader-cart{margin:10px auto;}
.loader-cart::before,.loader-cart::after{content:'';display:inline-block;position:absolute;top:0;}
.loader-cart::before{left:-15px;animation-delay:0s;-webkit-animation-delay:0s;}
.loader-cart::after{left:15px;animation-delay:1s;-webkit-animation-delay:1s;}
.loader-cart{position:relative;padding:0!important;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-box-pack:center;-ms-flex-pack:center;-moz-box-pack:center;justify-content:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;animation-delay:.5s;-webkit-animation-delay:.5s;}
.loader-cart,.loader-cart::before,.loader-cart::after{width:10px;height:10px;border-radius:100%;-o-border-radius:100%;-ms-border-radius:100%;-moz-border-radius:100%;-webkit-border-radius:100%;}
</b:section>

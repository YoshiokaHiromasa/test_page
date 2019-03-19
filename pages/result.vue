<template>
  <section>
    <div class="header BG-green-C-white">
        <div class="header-title">
          みんなの育毛剤
        </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-md-9">
          <div class="search-result">
            <div class="search-select-title">
              検索結果一覧
            </div>
              <div class="search-select">
                <div class="search-select-question">
                  ●探しているのは？
                </div>
                <div class="search-select-ans"　id="type">

                </div>
                 <div class="search-select-question">
                   ●性別は？
                </div>
                <div class="search-select-ans"　id="gender">

                </div>             
                <div class="search-select-question">
                  ●口コミは？
                </div>
                <div class="search-select-ans"　id="star">

                </div>              
                 <div class="search-select-question">
                  ●返金保証は？
                </div>
                <div class="search-select-ans"　id="security">

                </div>             
              </div>


            <div class="search-checkbox">
              <div class="search-checkbox-script">
                追加条件は
              </div>

              <div class="search-checkbox-list">
              <div class="seaech-add-checkbox" id="c1"></div>
              <div class="seaech-add-checkbox" id="c2"></div>
              <div class="seaech-add-checkbox" id="c3"></div>
              <div class="seaech-add-checkbox" id="c4"></div>
              <div class="seaech-add-checkbox" id="c5"></div>
              <div class="seaech-add-checkbox" id="c6"></div>
              <div class="seaech-add-checkbox" id="c7"></div>
              <div class="seaech-add-checkbox" id="c8"></div>
              </div>

              <div class="search-checkbox-script">
                で検索しました。
              </div>              
            </div>

              


          
          </div>
        
        
        
        
        </div>




        <div class="col-md-3">
          <div class="side-bar">
           <div class="ads d-none d-sm-block">
             <div class="ad1">
               <img src="chapup.jpg" class="img-fluid">
             </div>
             <div class="ad2">
               <img src="plantel.jpg" class="img-fluid">
             </div>
           </div>
           <div class="sidebar-rank">
             <div class="sidebar-rank-title BG-green-C-white">
               商品一覧
             </div>
             <div class="sidebar-rank-contents">
               <div class="sidebar-rank-content">
                 <img src="chapup (1).jpg">
                 <div class="sidebar-rank-sestumei">
                   <a href="#" >チャップアップ</a>
                   <br><div class="gold">★★★★★</div>
                 </div>
                 <div class="sidebar-rank-kaisetsu">
                   業界No.1、今売れている人気の育毛剤。口コミでも圧倒的な利...
                 </div>
               </div>
               <div class="sidebar-rank-content">
                 <img src="plantel (1).jpg">
                 <div class="sidebar-rank-sestumei">
                   <a href="#" >プランテルEX</a>
                   <br><div class="gold">★★★★★</div>
                 </div>
                 <div class="sidebar-rank-kaisetsu">
                   最新成分のリデンシルや独自成分のペブプロミンαを配合してい...
                 </div>
               </div>
               <div class="sidebar-rank-content">
                 <img src="iqos.png">
                 <div class="sidebar-rank-sestumei">
                   <a href="#" >イクオス</a>
                   <br><div class="gold">★★★★　</div>
                 </div>
                 <div class="sidebar-rank-kaisetsu">
                   サプリが＋1,080円するだけで付いてくるのでセットがお得！体...
                 </div>
               </div>
               <div class="sidebar-rank-content">
                 <img src="finjia.jpg">
                 <div class="sidebar-rank-sestumei">
                   <a href="#" >フィンジア</a>
                   <br><div class="gold">★★★★　</div>
                 </div>
                 <div class="sidebar-rank-kaisetsu">
                   キャピキシル等一般的な育毛剤に配合されていない成分が高濃...
                 </div>
               </div>
               <div class="sidebar-rank-content">
                 <img src="polypure.jpg">
                 <div class="sidebar-rank-sestumei">
                   <a href="#" >ポリピュア</a>
                   <br><div class="gold">★★★★　</div>
                 </div>
                 <div class="sidebar-rank-kaisetsu">
                   男女兼用で幅広い世代に愛され、どんな抜け毛にも最適！人気...
                 </div>
               </div>
             </div>
             <div class="sidebar-ichiran-title BG-green-C-white">
              ランキング一覧
             </div>
             <div class="sidebar-ichiran-contents">
               <div class="sidebar-ichiran-content">
                 <img src="emuji.png">
                 <a href="#">Ｍ字型薄毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="oji.png">
                 <a href="#">O字型薄毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="yuji.png">
                 <a href="#">U字型薄毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="kongo.png">
                 <a href="#">混合型薄毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="hosoge.png">
                 <a href="#">細毛・軟毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="zyosei.png">
                 <a href="#">女性の薄毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="wakahages.png">
                 <a href="#">若ハゲに効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="nukege.png">
                 <a href="#">抜け毛に効くランキング</a>
               </div>
               <div class="sidebar-ichiran-content">
                 <img src="emuji.png">
                 <a href="#">コスパが良いランキング</a>
               </div>
            <div class="sidebar-koramu-title BG-green-C-white">
              コラム一覧
            </div>
            <div class="sidebar-koramu-contents">
               <div class="sidebar-koramu-content">
                 <a href="#">なぜハゲるの？</a>
               </div>
                <div class="sidebar-koramu-content">
                 <a href="#">育毛剤に頼りたくない？そんな人へ</a>
               </div>
                <div class="sidebar-koramu-content">
                 <a href="#">育毛に効く食べもの10選</a>
               </div>
             </div>


             </div>

           </div>
          </div>          

        </div>

      </div>
    </div>

    <div class="footer">
      <div class="footer-content">
        <div class="row">
          <div class="col-3 d-none d-sm-block">
            <div class="footer-items">
              <div　class="footer-title"><a href="#">人気の育毛剤</a></div>
              <div class="footer-list">
                <a href="#">チャップアップ</a><br>
                <a href="#">プランテルEX</a><br>
                <a href="#">イクオス</a><br>
                <a href="#">フィンジア</a><br>
                <a href="#">ポリピュア</a><br>
              </div>
            </div>
          </div>
          <div class="col-3 d-none d-sm-block">
            <div class="footer-ranking">
              <div　class="footer-title"><a href="#">人気のランキング</a></div>
              <div class="footer-list">
                <a href="#">M字型薄毛に効くランキング</a><br>
                <a href="#">O字型薄毛に効くランキング</a><br>
                <a href="#">U字型薄毛に効くランキング</a><br>
                <a href="#">混合型薄毛に効くランキング</a><br>
                <a href="#">細毛・軟毛に効くランキング</a><br>
              </div>
            </div>
          </div>          
          <div class="col-3 d-none d-sm-block">
            <div class="footer-column">
              <div　class="footer-title"><a href="#">コラム一覧</a></div>
              <div class="footer-list">
                <a href="#">なぜハゲるの？</a><br>
                <a href="#">育毛剤に頼りたくない？そんな人へ</a><br>
                <a href="#">育毛に効く食べ物10選</a><br>
              </div>
            </div>

          </div>
           <div class="col-3">
             <div class="footer-about">
               <div　class="footer-title"><a href="#">サイトに関して</a></div>
              <div class="footer-list">
                <a href="#">運営者情報</a><br>
                <a href="#">調査概要</a><br>
                <a href="#">プライバシーポリシー</a><br>
              </div>
             </div>
          </div>
        </div>
      </div>
      <div class="Copyright">
        All rights reserved @ SunL
      </div>

    </div>


  </section>
</template>

<script>
export default {
  mounted: function () {
    var url_search = location.search.substr(1).split('&');

    var para = [];

    var key = null;

    for(var i = 0 ; i < url_search.length ; i++)
    {

      key = url_search[i].split("=");

      para[key[0]] = key[1];
    }

    var jp_type = 0;
    var jp_gender = 0;
    var jp_star = 0;
    var jp_security = 0;
    
    switch (para["type"]){
      case "1":
        jp_type="育毛剤";
        break;
      case "2":
        jp_type="シャンプー";
        break;
      case "3":
        jp_type="サプリ";
        break;
    }
    switch (para["gender"]){
      case "1":
        jp_gender="男性";
        break;
      case "2":
        jp_gender="女性";
        break;
      case "3":
        jp_gender="男女兼用";
        break;
    }
    switch (para["star"]){
      case "1":
        jp_star="★４以上";
        break;
      case "2":
        jp_star="★３以上";
        break;
      case "3":
        jp_star="★２以上";
        break;
      case "4":
        jp_star="★１以上";
        break;
    }
    switch (para["security"]){
      case "1":
        jp_security="あり";
        break;
      case "2":
        jp_security="なし";
        break;
    } 

    if (para["c1"]) {
       var jp_c1 = "M字型薄毛";
    }
    else{
      var jp_c1 = "　"
    }
    if (para["c2"]) {
      var jp_c2 = "U字型薄毛";
    }
    else{
      var jp_c2 = "　"
    }
    if (para["c3"]) {
      var jp_c3 = "コスパが良い";
    }
    else{
      var jp_c3 = "　"
    }
    if (para["c4"]) {
      var jp_c4 = "容量が多い";
    }
    else{
      var jp_c4 = "　"
    }
    if (para["c5"]) {
      var jp_c5 = "O字型薄毛";
    }
    else{
      var jp_c5 = "　"
    }
    if (para["c6"]) {
      var jp_c6 = "混合型薄毛";
    }
    else{
      var jp_c6 = "　"
    }
    if (para["c7"]) {
      var jp_c7 = "送料無料";
    }
    else{
      var jp_c7 = "　"
    }
    if (para["c8"]) {
      var jp_c8 = "医薬部外品";
    }
    else{
      var jp_c8 = "　"
    }

    document.getElementById("type").innerHTML=jp_type;
    document.getElementById("gender").innerHTML=jp_gender;
    document.getElementById("star").innerHTML=jp_star;
    document.getElementById("security").innerHTML=jp_security;
    document.getElementById("c1").innerHTML=jp_c1;
    document.getElementById("c2").innerHTML=jp_c2;
    document.getElementById("c3").innerHTML=jp_c3;
    document.getElementById("c4").innerHTML=jp_c4;
    document.getElementById("c5").innerHTML=jp_c5;
    document.getElementById("c6").innerHTML=jp_c6;
    document.getElementById("c7").innerHTML=jp_c7;
    document.getElementById("c8").innerHTML=jp_c8;
},
  methods: {

  }
}
</script>

<style>
.search-select-title{
  background-color:#28a745;
  color:white;
  height:35px;
  font-size:20px;
  margin-top:10px;
  padding-left:10px;
  padding-top:2px;
}

.search-select{
  padding:20px 10px;
  font-size:20px;
  width:100%;
}

.search-select-question{
  width:50%;
  float:left;
  
  padding:10px 0px;
  padding-left:20px;
}

.search-select-ans{
  width:50%;
  float:left;
  text-align:center;

  padding:10px 0px;
}
.seaech-add-checkbox{
  width:22%;
  float:left;
  text-align:center;
  font-size:19px;
  border-radius:10px;
  background-color:lightgreen;
  margin:10px;
}

.search-checkbox-script{
  font-size:20px;
  padding-left:30px;
}

.search-checkbox{
  
}

.search-result{
  
}

</style>

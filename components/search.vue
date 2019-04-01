<template>
          <div class="search">
            <form method="GET" action="result">
            <div class="search-title ">簡単検索でピッタリの育毛剤を探す</div>
            <div class="search-content">
              <div class="search-top">
                <div class="container">
                <div class="row">
                  <div class="col-sm-6 search-box">
                    <span class="search-question">１．探しているのは？</span>
                    <div class="search-select">
                      <select name="type">
                        <option value="1">育毛剤</option>
                        <option value="2">シャンプー</option>
                        <option value="3">サプリ</option>
                      </select>
                    </div>                   
                  </div>
                  <div class="col-sm-6 search-box">
                    ３．性別は？
                    <div class="search-select">
                      <select name="gender">
                        <option value="1">男性</option>
                        <option value="2">女性</option>
                        <option value="3">男女兼用</option>
                      </select>
                    </div>
                    </div>           
                  </div>
                  </div>
                </div>

              <div class="search-bottom">
                <div class="container"> 
                <div class="row">
                  <div class="col-sm-6 search-box">
                    <div class="search-question">２．口コミは気にする？</div>
                    <div class="search-select">
                      <select name="star">
                        <option value="1">★４以上</option>
                        <option value="2">★３以上</option>
                        <option value="3">★２以上</option>
                        <option value="4">★１以上</option>
                      </select>
                      </div>
                    </div>                               
                
                  <div class="col-sm-6 search-box">
                    <div class="search-question">４．返金保証は？</div>
                    <div class="search-select">
                      <select name="security">
                        <option value="1">返金保証あり</option>
                        <option value="2">返金保証なし</option>
                      </select>
                     </div> 
                     </div>
                  </div>
                  </div>
                                                 
                </div>
              
              
              


              <div class="search-checkbox">
                  <div class="hidden_box">
                  <div class="aa"><label for="label1">+条件を追加する</label></div>
                  <input class="vanish" type="checkbox" id="label1"/>
                  <div class="hidden_show">
                    <div class="row search-checkbox-content">
                      <div class="col-6 box-left">
                        <div class="box-s"><p><input type="checkbox" name="c1" value="1">M字型薄毛</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c2" value="1">U字型薄毛</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c3" value="1">コスパが良い</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c4" value="1">容量が多い</p></div>
                      </div>
                      <div class="col-6 box-right">
                        <div class="box-s"><p><input type="checkbox" name="c5" value="1">O字型薄毛</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c6" value="1">混合型薄毛</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c7" value="1">送料無料</p></div>
                        <div class="box-s"><p><input type="checkbox" name="c8" value="1">医薬部外品</p></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              </div>

              <div class="search-btn">
                 <input type="submit" value="この条件で探す" >
              </div>
              </form>


            </div>
</template>

<script>
export default {
    
}
</script>

<style>
.search{
  margin-top:10px;
}

.search-title {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
  padding-left:10px;
}

.search-box{
  border:0.5px#dee2e6 solid;
  padding:10px;
}

.search-question{
  float:left;
  font-size:16px;
}

.search-select{
  font-size:16px;
  float:right;
  width:40%;
}

.search-select select{
  width:100%;
  border-radius:2px;
}

.search-question{
  width:55%;
}
.search-top{
  padding:5px 0px;
}
.search-bottom{
  padding:5px 0px;
}

.search-content{
  background-color:#f8f9fa;
  padding-top:10px;
}
.search-btn{
  text-align:center;
}

.search-btn input{
  background-color:#38b48b;
  width:90%;
  height:50px;
  border-radius:5px;
  color:white;
  font-size:24px;
}
.hidden_box {
    margin: 10px 0;/*前後の余白*/
    padding: 0;
    float:center;
    text-align: center;
}

.hidden_box label {
    padding: 5px;
    font-weight: bold;
    border: solid 2px black;
    cursor :pointer;
    margin-bottom:5px;
    border:solid 1px gray;
    border-radius: 5px;
    color:white;
    background-color: gray;
    opacity: 0.7;
}

.hidden_box label:hover {
    opacity: 1;
}

.vanish {
    display: none;
}

.hidden_box .hidden_show {
    height: 0;
    padding: 0;
    overflow: hidden;
    opacity: 0;
    transition: 0.8s;
}

.hidden_box input:checked ~ .hidden_show {
    padding: 10px 0;
    height: auto;
    opacity: 1;
}

</style>
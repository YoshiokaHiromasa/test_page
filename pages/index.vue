<template>
  <section class="container">

    <div class="header">
        <div class="header-title WG">
          みんなの育毛剤
        </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-9">
          <div class="main">
            <div class="main-header">
               <img src="top-header.png" class="img-fluid">
            </div>
            <div class="sarch">
              <div class="sarch-title WG">
                簡単検索でピッタリの育毛剤を探す
              </div>
              <div class="sarch-content">
                この中に検索ページが入る。
              </div>
              <div class="ranking">
                <div class="ranking-header">
                  <img src="ranking-header.png" class="img-fluid">
                </div>
                <div class="ranking-contents">
                  <div class="ranking-content">
                    <div class="ranking-title">第１位　<a href="#">チャップアップ</a></div>
                      <div class="ranking-top">
                        <div class="container">
                          <div class="row">
                            <div class="col-4">
                              <img src="chapup (1).jpg" class="img-fluid">
                            </div>
                            <div class="col-8">
                              <div class="ranking-naiyo">
                                ★★★★★　4.7（口コミ320件）
                                <br>販売価格：￥7,400
                                <p class="red">割引率：今だけ32％ OFF</p>
                              </div>
                            </div>

                          </div>

                        </div>
                      </div>

                      <div class="table1">
                        <div class="table">
                          <table>
                            <tr>
                              <th>内容量</th><th>成分</th><th>返金補修</th><th>医薬部外品</th>
                            </tr>
                            <tr>
                              <td><div class="STU">120ml<br>(1か月)</div></td><td>73種類</td><td><div calss="red">◎<br>（永久保証）</div></td><td>〇</td>
                            </tr>
                          </table>
                        </div>
                      </div>

                  </div>
                </div>

              </div>
            </div>

          </div>
        </div>
        <div class="col-3">
          <div class="side-bar">
            ブロック２
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
    </div>

  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}


</script>

<style>

.table1{
  width:100%;
}

.ranking-top{
  margin-top:10px;
  font-size:24px;
}

.red{
  color:red;
}


.ranking-title{
  font-size:30px;
}

.ranking{

}

.main{
  height:4000px;
}
.side-bar{
  height:4000px;
}

.main-header{
  padding-top:8px;
}


.sarch-title{
  padding-top:5px;
  padding-left:5px;
}

.sarch-content{
  width:100%;
  text-align:center;
  height:400px;
  background-color:snow;
  font-size: 30px;
  padding-top:150px;
}

.WG{
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
}

.header{

}

.header-title{
  font-size:20px;
}

.col-9{
  background-color:snow;
}

.col-3{
  background-color:gray;
}

</style>

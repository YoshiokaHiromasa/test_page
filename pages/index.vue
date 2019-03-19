<template>
  <section>
  <mainheader/>

  <div class="search-title">
    簡単検索でピッタリの育毛剤を探す
  </div>
  <div class="search-content">
    この中に検索ページが入る。
  </div>

  <rankingheader/>
  <div class="ranking">
    <chapup/>
    <plantel/>
    <iqos/>
    <finjia/>
  </div>

</section>
</template>

<script>
import chapup from '~/components/items/chapup.vue'
import plantel from '~/components/items/plantel.vue'
import iqos from '~/components/items/iqos.vue'
import finjia from '~/components/items/finjia.vue'
import rankingheader from '~/components/ranking-header.vue'
import mainheader from '~/components/main-header.vue'
export default {
  components: {
    chapup,
    plantel,
    iqos,
    finjia,
    rankingheader,
    mainheader
  }
}

</script>

<style>

.sidebar-koramu-title {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px; 
}

.sidebar-ichiran-title {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
}

.sidebar-rank-title {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
}

.search-title {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
  padding-left:10px;
}

.header {
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
}
.item-image  {
  width:100px;
  height:100px;
}

.compare-table {
  width:100%;
  border-collapse:  collapse;
  table-layout: auto;
}

.figure img {
  width:50%;
  height:50%;
}

.compare-table th {
  padding-left:10px;
  padding-right:10px;
  font-size:16px;
  height:50px;
  color:#495057;
  border: solid 1px #dee2e6;
  background-color:#e9ecef;
}

.compare-table td {
  font-size:16px;
  border: solid 1px lightgray;
  padding:10px;
  text-align: center;
}

.compare-title {
  margin-top:10px;
  padding-top:4px;
  padding-left:5px;
  background-color:#28a745;
  color:white;
  height:40px;
  width:100%;
  font-size:20px;
}


.main-header {
  padding-top:8px;
}

.ranking{
  padding-bottom:20px;
}
</style>

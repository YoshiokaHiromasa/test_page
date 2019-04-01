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
    <compare/>
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
import compare from '~/components/compare.vue'
export default {
  components: {
    chapup,
    plantel,
    iqos,
    finjia,
    rankingheader,
    mainheader,
    compare
  }
}

</script>

<style>


</style>

<template>
  <div>
    <div class="header ">
      <div class="header-title">
        みんなの育毛剤
      </div>
   </div> 
   <div class="container">
   <div class="row">
     <div class="col-sm-9">
       <nuxt/>
     </div>
     <div class="col-sm-3">
       <sidebar/>
     </div>
    </div>
   </div>
   <footer/>
  </div>
</template>
<script>
import sidebar from '~/components/sidebar.vue'
import footer from '~/components/footer.vue'

export default {
  components: {
    sidebar,
    footer
  }

}
</script>

<style>
.search-btn {
  font-size:20px;
  float:center;
}

.hidden_box {
    margin: 20px 0;/*前後の余白*/
    padding: 0;
    float:center;
    text-align: center;
}

.hidden_box label {
    padding: 15px;
    font-weight: bold;
    border: solid 2px black;
    cursor :pointer;
    margin-bottom:40px;
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


.search-question {
  width:60%;
  margin:0px;
}
.search-select select {
  float:right;
  border-radius: 5px;
  height:40px;
  font-size:16px;
  padding-left:5px;
  width:40%;
}

.footer_list a {
  text-decoration:none;
  color:white;
}

.footer_title a {
  text-decoration:none;
  color:white;
}

.footer-list {
  text-align: center;
  padding-left:10px;
}

.Copyright {
  padding-top:15px;
  color:white;
  text-align: center;
  margin-bottom:15px;
}

.footer-title {
  text-align: center;
  font-size:20px;
  margin-bottom:5px;
}

.footer {
  text-align: center;
  width:100%;
  background-color:#28a745;
  color:white;
  font-size:17px;
}

.review-name {
  font-size:16px;
  padding:7px 4px;
}

.review-content {
  padding:0px 4px;
  font-size:13px;
  border-bottom:1.5px solid silver;
  padding-bottom:10px;
}

.review-title {
  background-color: #ffc107;
  color:white;
  font-size:20px;
  padding-top:3px;
  padding-left:5px;
  margin-top:5px;
}

.ranking-title {
  font-size:30px;
}

.ranking-top {
  margin-top:10px;
  font-size:24px;
}

.red {
  color:red;
}

.setsumei {
  margin-top:5px;
  margin-bottom:5px;
  border: 1px solid lightgray;
}

.product-features {
  margin-top:10px;
}
.product-features table  {
  width:100%;
  border-collapse:  collapse;
}

.product-features th {
  padding:13px 10px;
  background-color:lightgray;
  color:dimgray;
  text-align: center;
  border: solid 1px lightgray;
}

 .product-features td {
  padding:10px 10px;
  background-color:white;
  margin:auto;
  text-align: center;
  border: solid 1px lightgray;
}

.ranking-content {
  border-bottom:dashed 3px gray;
  padding-bottom:15px;
}

.Scoop-info-title {
  background-color: whitesmoke;
  text-align: center;
  border: 1px solid whitesmoke;
  height:35px;
  padding-top:4px;
}

.Scoop-info-content {
 border: 1px solid whitesmoke;
 padding-top:8px;
 padding-left:5px;
 padding-right:5px;
}

.Scoop-info {
  margin-top:10px;
}

.btn1:hover {
  background-color:#38b48b;
  color:white
}

.btn2:hover {
  background-color:#e9546b;
  color:white
}

.btn {
  border-radius:5px;
  height:110px;
  padding-top:14px;
  color:white;
  font-size:28px;
}

.btn1 {
background-color: #00a497;
}

.btn2 {
background-color: #d3381c;
}


.setsumei {
  padding:10px 5px;
}

.sidebar-koramu-content {
  padding-top:7px;
}

.sidebar-ichiran-content img {
  margin-left:1px;
  height:21px;
  width:21px;
}

.sidebar-ichiran-title {
  margin-top:5px;
  padding-top:4px;
  padding-left:3px;
}

.sidebar-rank-kaisetsu {
  font-size:15px;
}

.gold {
  color:gold;
}

.sidebar-rank-sestumei {
  float:right;
  font-size:20px;
}

.sidebar-rank-content {
  padding-top:10px;
}
.sidebar-rank-content img {
  width:65px;
  height:65px;
}
.sidebar-rank-title {
  margin-top:5px;
  padding-top:4px;
  padding-left:3px;
}

.ads {
  padding-top:10px;
}

.footer a {
  color:white;
}

.header {
}

.header-title {
  width:160px;
  font-size:20px;
  padding-top:3px;
  padding-left:5px;
}

html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

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

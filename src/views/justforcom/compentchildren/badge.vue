<template>
  <div class="zuiwai">
      <h3 class="mytitle">基本样式</h3>
     <div class="showbadge">
          <fan-badge
          :value="122"
        >
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="primary"
      :value="15">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="warning"
      :value="2">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="info"
      :value="30">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>
     </div>
    
    <div class="showdiv">
        
    </div>


        <h3 class="mytitle">最大值</h3>
     <div class="showbadge">
          <fan-badge
          :value="122"
          :max="100"
        >
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="primary"
      :value="15"
       :max="10">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="warning"
      :value="2"
       :max="1">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
      type="info"
      :value="30"
       :max="29">
          <fan-btn >fanafn</fan-btn>
    </fan-badge>
     </div>


     <div class="showdiv">
        
    </div>


        <h3 class="mytitle">定义新内容</h3>
     <div class="showbadge">
          <fan-badge
          value="new"
         
        >
          <fan-btn >fanafn</fan-btn>
    </fan-badge>

       <fan-badge
        value="hot"
       >
          <fan-btn >fanafn</fan-btn>
    </fan-badge>


       <fan-badge
      value="good"
       >
          <fan-btn >fanafn</fan-btn>
    </fan-badge>
     </div>

     <div class="showdiv">
        
    </div>


        <h3 class="mytitle">小圆点形式</h3>
     <div class="showbadge">
          <fan-badge
          isDot
        >
    
          <fan-btn >新数据</fan-btn>
    </fan-badge>


       <fan-badge
      isDot
       >
      <fan-btn type="primary"><i class="el-icon-upload el-icon--right"></i></fan-btn>
    </fan-badge>
     </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.mytitle{
    margin: 55px 0 20px 5%;
    font-weight: 400;
    color: #1f2f3d;
}
.zuiwai{
    margin-left: 20px;
}
.showbadge{
    display: flex;
    justify-content: space-around;
    width: 100%;
    border-bottom:1px solid gainsboro ;
    padding-bottom: 40px;
}

.showdiv{
    width: 100%;
    height: 40px;
}
</style>
<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <img class="rei" alt="rei" src="../assets/rei.png"> -->
    <!-- <HelloWorld hello="ようこそ"/> -->
    <h1>Hello World </h1>
    <h1>目次 </h1>

  　  <ol>
   　 <li>自己紹介</li>　　　
　　 　<li>アピールポイント</li>
    　<li>1.スキル</li>
　　　 <li>2.意識</li>
　　　 <li>コンタクトページ</li>
　  　</ol>
<!-- section -->
    <h1>自己紹介</h1>
    <ul>
      <li>名前：伊原　裕太</li>
      <li>出身：埼玉県川島町</li>
      <li>趣味：スポーツ（バスケ・サッカー・スノボ等）・麻雀・音楽フェス　etc</li>
      <li>最終学歴：埼玉県川越市立川越高等学校卒</li>
      <li>その他：ブリヂストンサイクル株式会社　新卒５年間勤務　工場管理課</li>
    </ul>

   <h2>アピールポイント</h2>
　 <h3>①スキル</h3>
　　　<ol>
     <li>VBA</li>
     <li>EXCEL操作</li>
　　　<li>PowerPoint</li>
     <li>?HTML</li>
     <li>?CSS</li>
     <li>?Javascript</li>
     <li>?WordPressでSEO</li>
    </ol>

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style>
.rei{
  width:100%;
}
</style>
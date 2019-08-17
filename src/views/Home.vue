<template>
  <div>
    <!-- 1ページ目　topで編集 -->
    <div class="top">
      <div class="title-field">
        <h1>伊原　裕太のmy　portfolio </h1>
       </div>
       <div class="mokuji">
        <h1>目次 </h1>
        <ul>
          <li>1.自己紹介</li>
          <li>2.アピールポイント</li>
          <li>2-1−スキル</li>
          <li>2-2意識</li>
          <li>3.コンタクトページ</li>
        </ul>
      </div>
    </div>
　　<!--2ページ目　syoukaiで編集 -->
    <div class="syoukai">
      <h2>1.自己紹介</h2>
      <ul>
        <li>名前：伊原　裕太</li>
        <li>出身：埼玉県川島町</li>
        <li>趣味：スポーツ（バスケ・サッカー・スノボ等）・麻雀・音楽フェス　etc</li>
        <li>最終学歴：埼玉県川越市立川越高等学校卒</li>
        <li>その他：ブリヂストンサイクル株式会社　新卒５年間勤務　工場管理課</li>
      </ul>
    </div>

    <div class="point">
      <h2>2.アピールポイント</h2>
      <div class="skil">
         <h3>2−1スキル</h3>
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

      <div class="ishiki">
       <h3>2−2　意識</h3>
        <p>某中小の自転車メーカーで、工場管理課として活動</p>
        <p>主に生産計画を作成・管理しながら生産性向上をもとに活動</p>
        <p>PDCAを回した現場力向上を実施。(活動報告の資料作成・発表実績あり)</p>
      </div>
    </div>

      <div class="contact">
        <h3>3.コンタクトページ</h3>
          <p>何かお問い合わせ等、ございましたら下記リンクまでお問い合わせ願います</p>
      </div>
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

<style lang="scss">
.top {
  background-color: rgb(225, 106, 106);
  width: 100%;
  height: 100vh;
  h1 {
    margin: 0;
  }
  .title-field {
    background-color: rgb(106, 167, 225);
    width: 100%;
    height: 50%;
  }
  .mokuji {
    background-color: rgb(106, 225, 173);
    width: 100%;
    height: 50%;
  }
}
</style>

<style lang="scss">
.syoukai {
 background-color: red;
 width: 100%;
 height: 100vh;
 h2{
   margin: 0;
 }
}
</style>

<style lang="scss">
.point {
 background-color: blue;
 width: 100%;
 height: 100vh;
 h2{
   margin: 0;
 }
}
</style>

<style lang="scss">
.contact {
 background-color: green;
 width: 100%;
 height: 100vh;
 h3{
   margin: 0;
 }
}
</style>
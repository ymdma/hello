<template>
  <section class="container">
    <h1 class="page2">
      Page2
    </h1>
    <section>
      テスト：h1にクラスをあてて表示ずれの回避
    </section>
    <div>
      <router-link to="/page3">Page3へ</router-link>
      <router-link to="/">Topへ戻る</router-link>
    </div>
  </section>
</template>


<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}
h1.page2{
  margin: 0 0 0 0;
}
</style>
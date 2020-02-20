<template>
  <section class="container">
    <h1>
      Page3
    </h1>
    <section>
      テスト：h1にクラスなし
    </section>
    <div class="links">
      <router-link to="/page2">Page2へ</router-link>
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

</style>
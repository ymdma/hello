<template>
  <div class="container">

    <section class="title-view">
      <logo />
      <Hello />
    </section>

  <section class="message">
    <h2>
      {{ message }}
    </h2>
  </section>

  </div>


</template>

<script>
import Logo from '~/components/Logo.vue'
import Hello from '~/components/Hello.vue'

export default {
  data: function() {
    return {
      message: "My first Nuxt Project!"
    }
  },
  components: {
    Logo,
    Hello
  }
}
</script>

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
.title-view{
  width: 100%;
  height:100%;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.message{
  margin: 40px 0 0 0;
}

</style>

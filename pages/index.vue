<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title padded">
        nuxt-vuex-persist-shared-mutations-example
      </h1>
      <h2 class="subtitle padded">
        My dazzling Nuxt.js project
      </h2>
      <div class="main padded">
        <div class="padded">
          <h1>{{ $store.state.count }}</h1>
          <button @click="$store.commit('decrement');">-</button>
          <button @click="$store.commit('increment');">+</button>
        </div>
        <div class="padded">
          <ol>
            <li>Open this example in multiple tabs and play with (+), (-) buttons.</li>
            <li>Reload page - and/or re-open in new tab/windows.</li>
          </ol>
        </div>
      </div>
      <div class="padded">
        <a
          href="https://github.com/hartmut-co-uk/nuxt-vuex-persist-shared-mutations-example"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
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
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 32px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 20px;
  color: #526488;
  word-spacing: 5px;
}

.padded {
  padding-bottom: 15px;
}
</style>

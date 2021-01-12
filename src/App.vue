<template>
  <div id="app">
    <v-main :api="apiKey"/>
  </div>
</template>

<script>


import VMain from "@/components/v-main";

export default {
  name: 'App',
  components: {VMain},
  data() {
    return {
      apiKey: '35bdf1f0e96270480e84bf6b192a5a48',

    }
  }
}
</script>

<style>

</style>

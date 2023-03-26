<template>
  <div id="app">
    <elInputExtends v-model="input" show-password/>
  </div>
</template>

<script>
import elInputExtends from './components/el-input-extends.vue'
export default {
  name: 'App',
  components: {
    elInputExtends
  },
  data(){
    return {
      showPassword:false,
      input:''
    }
  }
}
</script>

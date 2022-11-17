<script>

import AppSearch from './components/AppSearch.vue';
import HeaderApp from './components/HeaderApp.vue';
import CharacterList from './components/CharacterList.vue';
  
  export default {
    name: 'App',
    components:{
      HeaderApp,
      AppSearch,
      CharacterList
    }
  }
</script>

<template>
  
  <HeaderApp title="BreakingBad"/>
  <main>
    <AppSearch/>
    <CharacterList/>
  </main>



</template>


<style lang="scss">
@use './styles/general.scss'

</style>
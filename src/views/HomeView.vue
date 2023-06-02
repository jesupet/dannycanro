<template>
   <div class="background-image">
    <NavBar/>
    <header class="container align-items-center">
      <div class="header-text">
      </div>
    </header>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
  }
}
</script>

<template>
  <v-container>
    <div id="component-profile" class="d-flex flex-column justify-center align-center">
      <img src="~assets/img/profile.jpg" alt="profile" />
      <h1>{{ name }}</h1>
      <p>{{ description }}</p>
      <div class="d-flex">
        <a href="https://www.linkedin.com/in/robertsiagian21/" target="_blank" title="Linkedin"><i class="fab fa-linkedin mx-2"></i></a>
        <a href="mailto:roberthussebastians@gmail.com" target="_blank" title="Email"><i class="far fa-envelope mx-2"></i></a>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      name: 'Roberthus Sebastian Siagian',
      description: 'I am a Fresh Graduates from Telkom University'
    }
  }
}
</script>

<style scoped lang="scss">
#component-profile {
  height: 100vh;
  img {
    max-height: 200px;
    border-radius: 100px;
  }
  i {
    font-size: 44px;
    color: orange;
  }
}
</style>

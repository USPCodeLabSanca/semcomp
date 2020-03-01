<template>
  <div>
    <Jumbotron />
    <About />
    <Numbers />
    <Sponsors />
  </div>
</template>

<script>
import Jumbotron from '~/components/Jumbotron.vue'
import About from '~/components/About.vue'
import Numbers from '~/components/Numbers.vue'
import Sponsors from '~/components/Sponsors.vue'

export default {
  components: {
    Jumbotron,
    About,
    Numbers,
    Sponsors
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.bg-primary {
  background-color: #115079;
}

.bg-secondary {
  background-color: #303030;
}

a {
  text-decoration: none;
}

:focus {
  outline: 0px;
}

.title {
  font-size: 48px;
}

.subtitle {
  font-size: 24px;
}

.subtitle2 {
  font-size: 18px;
}

@media (min-width: 768px) {
  .title {
    font-size: 64px;
  }

  .subtitle {
    font-size: 32px;
  }

  .subtitle2 {
    font-size: 24px;
  }
}
</style>

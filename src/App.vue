<script setup>
import WelcomeBanner from './components/WelcomeBanner.vue'
import ExperienceList from './components/ExperienceList.vue'
</script>

<template>
  <header>
    <img alt="" class="logo" src="./assets/juan_face_2023.jpg" />

    <div class="wrapper">
      <WelcomeBanner msg="22 years moving user-focused organizations forward." />
    </div>
  </header>

  <main>
    <ExperienceList />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  aspect-ratio: 1/1;
  max-width: 50%;
  border-radius: 5px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

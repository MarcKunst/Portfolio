<template>
    <section id="about-section">
        <AboutTitle></AboutTitle>
        <AboutContainer></AboutContainer>
    </section>
</template>

<script>
import AboutTitle from '~/components/about/AboutTitle.vue'
import AboutContainer from '~/components/about/AboutContainer.vue'

export default {
  components: {
      AboutTitle,
      AboutContainer
  }
}
</script>

<style scoped>

#about-section {
    width: 100%;
    display: grid;
    grid-template-rows: 30% 70%;
    background-color: #fdfdfd;
    padding: 4rem 4rem 10rem;

}

@media (min-width: 1025px) {
    #about-section{
    padding: 4rem 15rem 10rem;
    }
}

</style>
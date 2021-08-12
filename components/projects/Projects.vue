<template>
    <section id="project-section">
        <ProjectsTitle></ProjectsTitle>
        <ProjectContainer></ProjectContainer>
    </section>
</template>

<script>
import ProjectsTitle from '~/components/projects/ProjectsTitle.vue'
import ProjectContainer from '~/components/projects/ProjectContainer.vue'

export default {
  components: {
      ProjectsTitle,
      ProjectContainer
  }
}
</script>

<style scoped>

#project-section {
    width: 100%;
    background-color: #fdfdfd;
    display: grid;
    padding: 4rem 4rem;
    /* background-image: url(../../assets/images/project-bg.png);
    background-position: bottom;
    background-size: contain;
    background-repeat: no-repeat; */

}

@media (min-width: 1024px) {
    #project-section{
    padding: 4rem 15rem;
    }
}

/* @media (min-width: 1025px) {
    #project-section{
    padding: 4rem 4rem;
    }
} */

</style>
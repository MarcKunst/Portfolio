<template>
    <section id="snippets-section">
        <SnippetsTitle></SnippetsTitle>
        <SnippetsContainer></SnippetsContainer>
    </section>
</template>

<script>
import SnippetsTitle from '~/components/snippets/SnippetsTitle.vue'
import SnippetsContainer from '~/components/snippets/SnippetsContainer.vue'

export default {
  components: {
       SnippetsTitle,
       SnippetsContainer
  }
}
</script>

<style scoped>

#snippets-section {
    width: 100%;
    background-color: #fdfdfd;
    display: grid;
    padding: 4rem 4rem 15rem;
    background-position: bottom;
    background-size: contain;
    background-repeat: no-repeat;

}

@media (min-width: 1025px) {
    #snippets-section{
    padding: 4rem 15rem 15rem;
    }
}

</style>
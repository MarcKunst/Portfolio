<template>
    <section id="project-container">
        <nuxt-link class="project-article" to="/pingping">
            <article id="pingping">
                <h3>PING PING</h3>
                <div class="underline pingping-line"></div>
                <p class="job-desc">UX Design | UI design</p>
                <p class="info">An app developed for the municipality of Amsterdam. The app helps young people to stay out of debt.</p>
            </article>
        </nuxt-link>
        <nuxt-link class="project-article" to="/pip">
            <article id="pip">
                <h3>PIP</h3>
                <div class="underline pip-line"></div>
                <p class="job-desc">UX Design | UI design</p>
                <p class="info">This app helps immigrants with their integration process. This app has a strong emphasis on accessibility.</p>
            </article>
        </nuxt-link>
        <nuxt-link class="project-article" to="/fabschoolino">
            <article id="fabschoolino">
                <h3>FABSCHOOLINO</h3>
                <div class="underline fabschoolino-line"></div>
                <p class="job-desc">Frontend | Engineering</p>
                <p class="info">I carried out this project during my internship at Waag Society. We gave arduino worshops with children.</p>
            </article>
        </nuxt-link>
                <nuxt-link class="project-article" to="/stubu">
            <article id="stubu">
                <h3>STUBU</h3>
                <div class="underline stubu-line"></div>
                <p class="job-desc">Frontend</p>
                <p class="info">I created an app where students can caculate the student debt. The can get insight in their budget and can listen to stories of other students.</p>
            </article>
        </nuxt-link>
        <nuxt-link class="project-article" to="/puma">
            <article id="puma">
                <h3>PUMA</h3>
                <div class="underline puma-line"></div>
                <p class="job-desc">Frontend | Design</p>
                <p class="info">I worked on a data visualization to see how much steel and copper there is in the foundations of buildings in the Netherlands.</p>
            </article>
        </nuxt-link>
        <nuxt-link class="project-article" to="/stickyricky">
            <article id="stickyricky">
                <h3>STICKY RICKY</h3>
                <div class="underline ricky-line"></div>
                <p class="job-desc">Game design | Development</p>
                <p class="info">I made a 2D platformer in Unity in which the player has to stick to the walls to finish the game.</p>
            </article>
        </nuxt-link>
        <nuxt-link class="project-article" to="/lift">
            <article id="lift">
                <h3>LIFT</h3>
                <div class="underline lift-line"></div>
                <p class="job-desc">UX Design | UI Design</p>
                <p class="info">With a group we made an app that allows young people with mild disabilities to come into contact with each other.</p>
            </article>
        </nuxt-link>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#project-container {
    width: 100%;
    height: 100%;
    display: grid;
    row-gap: 2.5rem;
    grid-template-columns: repeat( auto-fill, minmax(20rem, 1fr) );
    column-gap: 2.5rem;
}

.project-article {
    text-decoration: none;
}

.project-article:hover > article {
    box-shadow: 0rem 0.7rem 1rem 0rem rgb(105, 105, 105);
}

article {
    height: 25rem;
    padding: 2rem;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    box-shadow: 0rem 0.5rem 1rem 0rem rgb(163, 163, 163);
    transition: box-shadow 300ms;
}

h3 {
    font-family: Didot;
    font-style: italic;
    font-size: 1.8rem;
    font-weight: 100;
    padding-left: 0.15rem;
    color: #fdfdfd;
    width: 100%;
}

.job-desc {
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    letter-spacing: 1px;
    font-weight: 500;
    color: #fdfdfd;
    padding-bottom: 1rem;
}

.info {
    font-family: 'Montserrat', sans-serif;
    font-size: 0.8rem;
    letter-spacing: 1px;
    font-weight: 400;
    color: #fdfdfd;
    text-align: justify;
}

#pingping {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),
    url(../../assets/images/pingping.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

#stubu {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),
    url(../../assets/images/stubu.jpg);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#pip {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),
    url(../../assets/images/pip.png);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#fabschoolino {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/fabschoolino.jpg);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#puma {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/puma.jpg);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#stickyricky {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/stickyricky.jpg);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#lift {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/lift.jpg);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

.underline {
    height: 1px;
    width: 19rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.pingping-line {
    width: 8rem;
}

.stubu-line {
    width: 4.5rem;
}

.pip-line {
    width: 2rem;
}

.fabschoolino-line {
    width: 13rem;
}

.puma-line {
    width: 4rem;
}

.ricky-line {
    width: 11rem;
}

.lift-line {
    width: 3rem;
}

</style>
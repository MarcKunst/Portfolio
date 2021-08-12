<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>MY ROLE</h3>
                <div class="role-line"></div>
                <p>I worked on this project with two designer. I was the developer of the team. It was my responsibility to translate the designs to a usable product. I decided to use nuxt.js. There wasn't much time for this project so I needed a framework that would solve a lot of things for me so I could focus on the details. For more information about my code please check out my <a target="blank" href=https://github.com/MarcKunst/nibud>Github</a>
                </p>
            </article>
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>HTML 5</li>
                        <li>CSS 3</li>
                        <li>Nuxt.JS</li>
                        <li>Graph.JS</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>During my study I did a course called "Information design". The Nibud gave us the assignment to create a data visualisation for students to raise awareness for their student debts.</p>
            </article>
        </section>
        <section id="debt">
            <article>
                <h3 class="feature-headers">CALCULATING DEBT</h3>
                <div class="core-line"></div>
                <p>For the first part of our project we wanted to show the students how big their debts could become. We also wanted to show how big this debt is in commparison to other students. To do this, I made sure that the local storage would save all the data from the previous screens. This data would later on be shown in a bubble chart that compares the calculated the debt to the average debt of the dutch students.</p>
            </article>
            <img class="screen-img" src="../../assets/images/stubu1.png" alt="image of the event screen">
            <img class="screen-img" src="../../assets/images/stubu2.png" alt="image of the overview screen">
        </section>
        <section id="budget">
                <article>
                <h3 class="feature-headers">BUDGET</h3>
                <div class="core-line xshort"></div>
                <p>The next step was to give the students insight in their budget. We took the most common sources of income and expenditure. After the student had filled in their data, we would show the student how much money they earned and how much the spend.</p>
            </article>
            <img class="screen-img" src="../../assets/images/stubu3.png" alt="image of the event screen">
            <img class="screen-img" src="../../assets/images/stubu4.png" alt="image of the overview screen">
        </section>
        <section id="stories">
            <article>
                <h3 class="feature-headers">STORIES</h3>
                <div class="core-line xshort"></div>
                <p>At the end of the experience we would let the students hear stories of other students. We recorded audioclips from actual students.
                </p>
            </article>
            <img class="screen-img" src="../../assets/images/stubu5.png" alt="image of the event screen">
            <img class="screen-img" src="../../assets/images/stubu6.png" alt="image of the overview screen">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://stubu.netlify.app/" target="blank">
                See the final product
            </a>
            <a id="view-project-button" href="https://github.com/MarcKunst/nibud" target="blank">
                Check Github repo
            </a>
        </section>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#pingping-container {
    height: 100%;
    margin: 4rem;
    
}

#role {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 4rem;
    margin-bottom: 3rem;
}

#assignment {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 4rem;
}

#debt {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#budget {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#stories {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

.screen-img {
    width: 15rem;
    box-shadow: 0rem 0.5rem 1rem 0rem rgb(163, 163, 163);
    border-radius: 8px;
    
}

article {
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    text-align: justify;
    letter-spacing: 1px;
}

h3 {
    font-family: Didot;
    font-style: italic;
    font-size: 1.5rem;
    font-weight: 100;
    padding-left: 0.15rem;
    padding-top: 3rem;
}

.feature-headers {
    padding-top: 0rem;
}

.role-line {
    height: 1px;
    width: 6rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.tools-line {
    height: 1px;
    width: 10rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.assignment-line {
    height: 1px;
    width: 15rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.core-line {
    height: 1px;
    width: 15rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.medium {
    font-weight: 500;
    font-size: 1.1rem;
}

.short {
    width: 10rem;
}

.xshort {
    width: 6rem;
}

ul {
    padding: 0;
    list-style: none;
}

#button-wrapper {
    display: flex;
    justify-content: center;
    margin-top: 5rem;
}

#view-project-button {
    width: 15rem;
    height: 4rem;
    background-color: #DDA681;
    border: 2px solid #fdfdfd;
    text-decoration: none;
    text-align: center;
    line-height: 3.8rem;
    font-family: 'Montserrat', sans-serif;
    color: #fdfdfd;
    font-weight: 500;
    transition: background-color 200ms;
}

#view-project-button:hover {
    background-color: rgb(202, 141, 100);
}

@media (max-width: 768px) {
    #role {
        grid-template-columns: 1fr;
    }

    #assignment {
    grid-template-columns: 1fr;
    }
}

@media (max-width: 1025px) {
    #pingping-container {
    margin: 4rem 15rem;
    
    }
    #debt {
    grid-template-columns: repeat(auto-fill, minmax(15rem, 1fr));
    }

    #budget {
    grid-template-columns: repeat(auto-fill, minmax(15rem, 1fr));
    }
    #stories {
    grid-template-columns: repeat(auto-fill, minmax(15rem, 1fr));
    }

#reward {
    grid-template-columns: repeat(auto-fill, minmax(15rem, 1fr));
    }
}

</style>
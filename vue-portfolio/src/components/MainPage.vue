<template>
    <div class="main-container">
        <div class="container1">
            <div class="profile">
                <img src="../assets/moonmoon.png" alt="">
                <h3>Kaixuan Khoo</h3>
                <p>Software Developer</p>
            </div>
            <div class="social-links">
                <a href="">
                    <img src="../assets/github.png" alt="">
                    <h2>Github</h2>
                </a>
                <a href="">
                    <img src="../assets/linkedin.png" alt="">
                    <h2>LinkedIn</h2>
                </a>
                <a href="">
                    <img src="../assets/twitter.png" alt="">
                    <h2>Twitter</h2>
                </a>
                <a href="">
                    <img src="../assets/discord.png" alt="">
                    <h2>Discord</h2>
                </a>
            </div>
        </div>
        <div class="container2">
            <div class="about-me">
                <h1>About Me</h1>
                <p>
                    I am a software developer for Content Guru.

                    I have an MSc in Computing Science from Imperial College London. 
                    I have a first class MSci in Chemistry with Medicinal Chemistry from Imperial too!
                </p>
            </div>
            <div class="technologies">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/CPlusPlus.svg" alt="">
                    <img src="../assets/CSharp.svg" alt="">
                    <img src="../assets/Java.svg" alt="">
                    <img src="../assets/JS.svg" alt="">
                    <img src="../assets/PHP.svg" alt="">
                    <img src="../assets/Python.svg" alt="">
                    <img src="../assets/MatLab.svg" alt="">
                </div>
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="">My Projects</a>
                </div>
                <div class="projects-button">
                    <a href="">My Resume</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    img{
        height: 30px;
    }

    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #1E3B83;
        border-radius: 20px;
    }

    .container1{
        padding: 2.5%;
        background-color: #5397C7;
        width: 25%;
        border-radius: 19px;
    }

    .profile img{
        height: 5rem;
        border-radius: 50%;
    }
    
    .social-links a{
        text-decoration: none;
        color: black;
        font-size: 10px;
    }

    .social-links img{
        height: 2rem;
    }
    .container2{
        background-color: #8DCCBC;
        width: 75%;
        margin: 2.5%;
        border-radius: 15px;
    }

    .about-me {
        padding: 2.5%;
        text-align: left;
    }

    .logos img{
        height: 2.5rem;
        padding: 5px;
    }

    .button-container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .projects-button{
        background-color: #ADAEB1;
        padding: 10px;
        margin: 5px;
        border-radius: 10px;
    }
    .projects-button a{
        text-decoration: none;
        font-size: 20px;
        color: #444444;
    }
    
</style>
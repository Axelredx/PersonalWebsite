<script setup>
import Navbar from '../components/navbar.vue';
</script>

<template>
    <Navbar />
    <div id="wrapper">
        <h1><b>Hello There!</b> <i class="fa-brands fa-jedi-order"></i></h1>
        <img src="/me.jpg" id="me" >
        <p>Welcome to my website, I'm Alex, here you can find some information about me, my projects.
            I'm really interested in Motors, Tech world and nerdy things such as Videogames or Cards.
        </p>
        <img id="imgwrapper" src="/linux_meme.jpg"> 
        <div id="info">
            <p>Some other info:</p>
            <ul>
                <li> Preferred OS: Linux (What else? [except for gaming :/ ])</li>
                <li> Preferred Plate: Pizza (obv, I'm italian)</li>
                <li> Fascinated by Space</li>
                <li> Yu-Gi-Oh and Chess enjoyer</li>
                <li> Biker dreamer</li>
            </ul>
        </div>       
    </div>
</template>

<style scoped>
#wrapper {
    width: auto;
    height: 78vh;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: column;
    /*border: solid white;*/
}

#imgwrapper {
    margin: 5px;
    background-color: aliceblue;
    height: 28%;
}

h1 {
    margin: 5px;
    color: white;
    font-size: 2em;
    text-align: center;
}

p {
    color: white;
    font-size: 1.5em;
    text-align:center;
}

#info{
    margin: 5px;
    color: white;
    font-size: 0.9em;
    text-align: justify;
}

#me {
    height: 70%;
    width: 25%;
    margin: 5px;
}

</style>

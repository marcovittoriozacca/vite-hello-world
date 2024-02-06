<script>
    export default{
        name: 'AppHero'
    }
</script>



<template>
  
    <div class="jumboContainer">

        <div class="jumboTitle">
            <img src="../assets/logo.svg" alt="vue-logo" width="80">
            <h2>Hero Banner</h2>
            <img src="../assets/logo.svg" alt="vue-logo" width="80">
        </div>
        <div class="jumboText">
            <p>An approachable, performant and versatile framework for building web user interfaces. </p>
        </div>

        <div class="jumboLink">
            <a href="https://vuejs.org/" target="_blank">Clicca per iniziare!</a>
        </div>
    </div>

</template>



<style scoped>

    .jumboContainer{
        background-color: rgba(0, 0, 0, 0.3);
        height: 400px;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        padding-bottom: 10px;
        
    }
    .jumboTitle{
     display: flex;
     column-gap: 20px;
     align-items: center;
    }
    h2{
        color: #41B883;
        font-size: 3rem;
    }
    .jumboText{
        font-size: 1.8rem;
        max-width: 75%;
        text-align: center;
    }
    p{
        color: white;
        transition: all .2s ease-in-out;
    }
    p:hover{
        color: #41B883;
    }
        
    a{
        text-decoration: none;
        color: white;
        border: .1px solid black;
        border-radius: 5px;
        padding: 20px 40px;
        background-color: rgb(30, 30, 30);
        font-weight: bold;
        font-size: 1.5rem;
        transition: all .2s ease-in-out;
    }
    a:hover{
        color: #41B883;
        background-color: #34495E;
    }

</style>

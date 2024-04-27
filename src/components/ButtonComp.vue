<template>
    <a href="https://bookem.co.za/" id="btn" class="btn">

        {{ btnContent="Workshops/seminars" }}

    </a>

    <a href="#about" id="btn" class="btn">

        {{ btnContent="One-on Coaching" }}

    </a>

    <a href="#FreeResources" id="btn" class="btn">

        {{ btnContent="Free resources" }}

    </a>

</template>

<script setup>
    defineProps({
     btnContent: String,
    })
</script>

<style scoped>

#btn {
    color: rgb(255, 255, 255);
    width: 20%;
    text-transform: uppercase;
    text-decoration: none;
    padding: 10px 5px;
    font-size: 15px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #48DD22;
    overflow: hidden;
    /* border-radius: 50px; */
    box-shadow: inset 10px 10px 10px 10px #2ba4152d;
}

#btn:hover {
    color: rgb(255, 255, 255);
}

#btn::after {
    content: '';
    position: absolute;
    height: 100%;
    width: 0%;
    top: 0;
    left: -50px;
    transform: skewX(0deg);
    background-color: #6eff693c;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
    z-index: 1;
    transition: all 0.6s;
}

#btn:hover::after{
    width: 180%;
}

@media (max-width: 800px) {
    #btn {
        color: rgb(255, 255, 255);
        width: 35%;
        text-transform: uppercase;
        text-decoration: none;
        padding: 10px 5px;
        font-size: 10px;
        font-weight: bold;
        background: transparent;
        position: relative;
        transition: all 0.3s;
        background-color: #48DD22;
        overflow: hidden;
        box-shadow: inset 10px 10px 10px 10px #2ba4152d;
    }

    #btn::after {
        content: '';
        position: absolute;
        height: 100%;
        width: 0%;
        top: 0;
        left: -50px;
        transform: skewX(50deg);
        background-color: #00000081;
        z-index: 1;
        transition: all 1s;
    }

    #btn:hover::after {
        width: 250%;
    }
}


@media (max-width: 400px) {
    #btn {
        color: rgb(255, 255, 255);
        width: 50%;
        text-transform: uppercase;
        text-decoration: none;
        padding: 10px 5px;
        font-size: 10px;
        font-weight: bold;
        background: transparent;
        position: relative;
        transition: all 0.3s;
        background-color: #48DD22;
        overflow: hidden;
        box-shadow: inset 10px 10px 10px 10px #2ba4152d;
    }

    #btn::after {
        content: '';
        position: absolute;
        height: 100%;
        width: 0%;
        top: 0;
        left: -50px;
        transform: skewX(50deg);
        background-color: #00000081;
        z-index: 1;
        transition: all 1s;
    }

    #btn:hover::after {
        width: 250%;
    }

}




@media (max-width: 325px) {
    #btn {
    color: rgb(255, 255, 255);
    width: 35%;
    text-transform: uppercase;
    text-decoration: none;
    padding: 10px 5px;
    font-size: 10px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #48DD22;
    overflow: hidden;
    box-shadow: inset 10px 10px 10px 10px #2ba4152d;
}

#btn::after {
    content: '';
    position: absolute;
    height: 100%;
    width: 0%;
    top: 0;
    left: -50px;
    transform: skewX(50deg);
    background-color: #00000081;
    z-index: 1;
    transition: all 1s;
}

}

</style>
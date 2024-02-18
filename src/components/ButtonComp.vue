<template>
    <a href="https://bookem.co.za/" id="btn" class="btn">

        workshops

    </a>

    <a href="#about" id="btn" class="btn">

        Know more <i class="fa-solid fa-arrow-right-long fa-sm" style="color: #ffffff;"></i>

    </a>

</template>

<script>
export default {
    
}
</script>

<style scoped>

#btn {
    color: rgb(255, 255, 255);
    width: 20%;
    text-transform: uppercase;
    text-decoration: none;
    border: none;
    padding: 10px 5px;
    font-size: 15px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #94e630;
    overflow: hidden;
    border-radius: 5px;
    box-shadow: inset 10px 10px 10px 10px #2ba4152d;
}

#btn:hover {
    color: rgb(14, 0, 108);
    /* mix-blend-mode: difference; */
}

#btn::after {
    content: '';
    position: absolute;
    height: 100%;
    width: 0%;
    top: 0;
    left: -50px;
    transform: skewX(50deg);
    background-color: #4aab2681;
    z-index: 1;
    transition: all 0.6s;
}

#btn:hover::after{
    width: 180%;
}

/* #btn::after {
    width: 87%;
} */

@media (max-width: 800px) {
    #btn {
    color: rgb(255, 255, 255);
    width: 35%;
    text-transform: uppercase;
    text-decoration: none;
    border: none;
    padding: 10px 5px;
    font-size: 10px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #94e630;
    overflow: hidden;
    border-radius: 5px;
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
    background-color: #ffffff68;
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
    width: 35%;
    text-transform: uppercase;
    text-decoration: none;
    border: none;
    padding: 10px 5px;
    font-size: 10px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #94e630;
    overflow: hidden;
    border-radius: 5px;
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
    background-color: #ffffff68;
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
    border: none;
    padding: 10px 5px;
    font-size: 10px;
    font-weight: bold;
    background: transparent;
    position: relative;
    transition: all 0.3s;
    background-color: #94e630;
    overflow: hidden;
    border-radius: 5px;
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
    background-color: #ffffff68;
    z-index: 1;
    transition: all 1s;
}

}

</style>
<template>
    <div class="info-container">
        <h2 text-primary>Dazzling Diamond Delights</h2>

        <div class="info-text">
            <div class="info">
                <p class="text-white">Stunning Solitaires</p>
                <p class="text-purple">Dive into our fantastic collection of solitaire <br> 
                rings showcasing brilliant craftsmanship.</p>
            </div>

            <div class="info">
                <p class="text-white">Exquisite Earrings</p>
                <p class="text-purple">Discover an array of diamond and gemstone <br>earrings designed to dazzle on every <br>occasion.</p>
            </div>

            <div class="info">
                <p class="text-white">Gorgeous Necklaces</p>
                <p class="text-purple">Unveil an exclusive selection of necklaces <br>adorned with mesmerizing diamonds and <br>gemstones.</p>
            </div>

            <div class="info">
                <p class="text-white">Beautiful Bracelets</p>
                <p class="text-purple">Explore our captivating assortment of <br>bracelets that make the perfect statement <br>piece.</p>
            </div>

            <div class="info">
                <p class="text-white">Glamorous Gemstones</p>
                <p class="text-purple">Indulge in a heavenly collection of precious <br>gemstones that are sure to turn heads.</p>
            </div>

            <div class="info">
                <p class="text-white">Custom Creations</p>
                <p class="text-purple">Craft your dream jewelery piece with our <br>experienced artisans catering to your every <br>need.</p>
            </div>


        </div>
    </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Goblin+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Old+Standard+TT:wght@400;700&display=swap');

.info-container {
    background-color: black;
    height: 50dvh;
    height: fit-content;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding-bottom: 5%;
}

.info-text {
    margin-top: 5%;
    margin-left: 2%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    width: 70dvw;
}

.info {
    margin-right: 5%;
}


h2 {
    margin: 0;
    padding-top: 5%;
    color: white;
    font-size: 48px;
    font-family: 'Goblin One', cursive;
    text-align: center;
    flex-direction: column;
}

.info {
    font-family: 'Old Standard TT', serif;
    font-size: 20px;
}

.text-white {
    color: white;
}

.text-purple {
    color: rgb(200, 177, 228);
}



</style>
<template>
    <div class="gallery-container">
        <div class="image-wrapper">
            <img class="image" src="../assets/img1.webp" alt="" >
            <p class="text-primary">Luxurious Diamonds</p>
            <p class="text-secondary">Experience the allure and essence of our <br>extraordinary diamond collection.</p>
        </div>

        <div class="image-wrapper">
            <img class="image" src="../assets/img2.webp" alt="">
            <p class="text-primary">Vibrant Gemstones</p>
            <p class="text-secondary">Embrace a world of color with our stunning <br>gemstone offerings.</p>
        </div>
    </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Goblin+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Old+Standard+TT:wght@400;700&display=swap');

.gallery-container {
    padding-top: 5%;
    background-color: #C8B1E4;
    display: flex;
    justify-content: space-around;
}

.image-wrapper {
}

.image {
    border-radius: 48px;
}

.text-primary {
    font-family: 'Goblin One', cursive;
    font-size: 32px;
}

.text-secondary {
    font-family: 'Old Standard TT', serif;
}

@media screen and (max-width: 800px) {
    .gallery-container {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .image {
        height: 25dvh;
        width: auto;
    }
}

</style>
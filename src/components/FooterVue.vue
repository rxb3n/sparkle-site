<template>
    <div class="footer-wrapper">
        <div class="footer-links">
            <img class="link" src="../assets/instagram-logo.png" alt="">
            <img class="link" src="../assets/twitter-logo.png" alt="">
            <img class="link" src="../assets/tiktok-logo.png" alt="">
        </div>

        <div class="footer-text">
            <p class="text-secondary">© 2023 Sparkle Jewelery</p>
        </div>
    </div>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Old+Standard+TT:wght@400;700&display=swap');

.footer-wrapper {
    background-color: #C8B1E4;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.footer-links {
    margin-top: 2%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.link {
    height: 5dvh;
    margin-right: 2%;
    filter: invert(12%) sepia(13%) saturate(7386%) hue-rotate(245deg) brightness(91%) contrast(99%);
}

.footer-text {
    text-align: center;
    margin-top: 2%;
}


.text-secondary {
    font-family: 'Old Standard TT', serif;
}


</style>
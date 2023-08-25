<template>
    <div class="contact-container">
        <div class="contact">
            <h3 class="text-primary">Contact Us</h3>
            <p class="text-secondary">Ready to elevate your style? Call +1-555-SPARKLE or email us at <br>support@sparkleandshine.com</p>
        </div>
        <button class="btn">Start Shopping</button>
    </div>

    <div class="separator">
        <img class="separator-img" src="../assets/diamond.png" alt="">
        <img class="separator-img" src="../assets/diamond.png" alt="">
        <img class="separator-img" src="../assets/diamond.png" alt="">
        <img class="separator-img" src="../assets/diamond.png" alt="">
        <img class="separator-img" src="../assets/diamond.png" alt="">
    </div>
</template>



<style scoped>

h3 {
    margin: 0;
}

.contact-container {
    padding-top: 8%;
    background-color: #C8B1E4;
    text-align: center;
}

.contact {
    display: flex;
    align-items: center;
    flex-direction: column;
}

.btn {
    background-color: #2F184B;
    border: none;
    border-radius: 8px;
    color: rgb(200, 177, 228);
    padding: 1%;
    max-width: 50%;
}

.text-primary {
    font-family: 'Goblin One', cursive;
    font-size: 48px;
}

.text-secondary {
    font-family: 'Old Standard TT', serif;
}

.separator {
    padding-top: 8%;
    padding-bottom: 5%;
    background-color: #C8B1E4;
    display: flex;
    justify-content: space-around;
}

.separator-img {
    height: 3%;
    width: 3%;
}

</style>
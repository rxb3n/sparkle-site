<template>
    <div class="hero-container">
        
        <div class="hero-text">
            <h1 class="text-primary">SPARKLE</h1>
            <h1 class="text-secondary">Jewelery</h1>
        </div>

        <div class="hero-svg">
            <svg viewBox="0 0 220 220" fill="none">
                <path d="M135.196 67L187.158 157C189.467 161 186.58 166 181.962 166H78.0385C73.4197 166 70.5329 161 72.8423 157L124.804 67C127.113 63 132.887 63 135.196 67Z" fill="rgb(47, 24, 75)" stroke="rgb(47, 24, 75)" stroke-width="8"></path>
                <path d="M115.196 67L167.158 157C169.467 161 166.58 166 161.962 166H58.0385C53.4197 166 50.5329 161 52.8423 157L104.804 67C107.113 63 112.887 63 115.196 67Z" stroke="rgb(83, 43, 136)" stroke-width="8" stroke-linejoin="round"></path>
            </svg>
        </div>
    </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Goblin+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Old+Standard+TT:wght@400;700&display=swap');

.hero-container {
    background-color: #9B72CF;
    display: flex;
    justify-content: space-around;
    text-align: center;
    width: 100%;
    height: 80dvh;
    align-items: center;
}

.hero-text {
    font-size: 50px;
}

.text-primary {
    font-family: 'Goblin One', cursive;
}
.text-secondary {
    font-family: 'Old Standard TT', serif;
    color: white;
    font-size: 3.5em;
}

svg {
    height: 30dvh;
}

h1 {
    margin: 0;
}

@media screen and (max-width: 950px) {
    .hero-container {
        display: block;
    }
    .hero-text {
        font-size: 4vw;
    }
}

</style>
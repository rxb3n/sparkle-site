<template>
<div class="faq-container">
    <h3 class="text-primary">Jewelery FAQ</h3>

    <div class="questions-wrapper">

        <div class="text-secondary question" >
            <p class="que">What is your return policy?</p>
            <p class="ans">To ensure your satisfaction, we offer a 30-day return <br>policy on all items purchased.</p>
        </div>

        <div class="text-secondary question">
            <p class="que">Do you offer customization?</p>
            <p class="ans">Absolutely! We are happy to work with you on creating a <br>unique, custom piece.</p>
        </div>

        <div class="text-secondary question">
            <p class="que">What payment methods do you accept?</p>
            <p class="ans">We accept Visa, MasterCard, American Express, PayPal, <br>and more.</p>
        </div>

        <div class="text-secondary question">
            <p class="que">What are your shipping options?</p>
            <p class="ans">We offer worldwide shipping with free express delivery <br>on all orders over $200.</p>
        </div>


    </div>
</div>

</template>


<style scoped>

h3 {
    margin: 0;
    padding: 0;
}
    .faq-container {
        background-color: #C8B1E4;
    }

    .questions-wrapper {
        padding-top: 5%;
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        flex-basis: 30%;
        align-items: center;
    }

    .question {

        margin-bottom: 2%;
    }

    .que {
        font-size: 24px;
    }



    .text-primary {
    text-align: center;
    font-family: 'Goblin One', cursive;
    font-size: 48px;
    color: #2F184B;
}

.text-secondary {
    font-family: 'Old Standard TT', serif;
    color: #2F184B;
}


</style>
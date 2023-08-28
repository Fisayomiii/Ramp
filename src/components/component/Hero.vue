<template>
    <div class="hero-container">
        <div class="container">
            <h1 class="hero-container-h1">Spending made smarter</h1>
            <p class="hero-container-paragraph">Easy-to-use cards, spend limits, approval flows, vendor payments, and
                more—plus an average savings of 3.5%.</p>


            <section class="section-newsletter">
                <div class="newsletter__ container container">
                    <form class="newsletter__form">
                        <input type="email" placeholder="Enter your email" class="newsletter__input" />
                        <button type='submit' class="button">Get Started</button>
                    </form>
                </div>

            </section>


            <form class="content">
                <input type="email" class="mail" placeholder="Enter your email">
                <button class="subscribe">Get Started</button>
            </form>

            <div class="paragraph-wrapper">
                <p class="paragraph">No personal credit checks or founder guarantee.</p>
            </div>

            <!-- images Fixed at the middle of left side -->
            <!-- <div class="fixed-at-side fixed-at-side--l">
                <img src="../../assets/64aa5db2fb7bf4cdf700d5ab_aa-end.svg" width="250" alt="" style="border-radius: 10%;">
            </div>

            <div class="fixed-at-side fixed-at-side--r">
                <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" width="350" alt=""
                    style="border-radius: 5%;">
            </div>

            <div class="sec-fixed-at-side sec-fixed-at-side--l">
                <img src="../../assets/64adc64449434c5dc98b0e8e_Homepage_Hero_02_25.jpg" width="400" alt=""
                    style="border-radius: 5%;">
            </div>

            <div class="sec-fixed-at-side sec-fixed-at-side--r">
                <img src="../../assets/64aa5db2fb7bf4cdf700d5ad_Ap.svg" width="300" alt="">
            </div>

            <div class="sec-fixed-at-center sec-fixed-at-center">
                <img src="../../assets/64adc64449434c5dc98b0e8e_Homepage_Hero_02_25.jpg" width="100" alt=""
                    style="border-radius: 10%;">
            </div> -->

        </div>
        <div class="side-imgs-wrapper">
            <div class="side-imgs side-imgs-list1">
                <img src="../../assets/64aa5db2fb7bf4cdf700d5ab_aa-end.svg" alt="">
            </div>

            <div class="side-imgs side-imgs-list2">
                <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" width="900" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
.hero-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 120vh;
    color: #fff;
    background-color: #787868;
    background-image: linear-gradient(rgba(0, 0, 0, .2), rgba(0, 0, 0, .2));
    background-attachment: fixed, scroll;
}

.container {
    width: 100%;
    max-width: 760px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

.container .hero-container-h1 {
    position: relative;
    z-index: 10;
    color: #fff;
    letter-spacing: -0.02em;
    font-size: 2.9em;
    font-weight: 700;
}

.container .hero-container-paragraph {
    position: relative;
    z-index: 10;
    text-align: center;
    margin: auto;
    max-width: 480px;
}

/*=============== NEWSLETTER ===============*/
.section-newsletter {
    margin-top: -8em;
    margin-bottom: -8em;
    padding: 10em;
}

.newsletter__form {
    position: relative;
    z-index: 10;
    display: flex;
    justify-content: space-between;
    border-width: 0;
    padding: .3rem;
    background: #B0B0A9;
    border-radius: .75rem;
    width: 100%;
    max-width: 500px;
}

.newsletter__input {
    color: #343434;
    background: none;
    width: 70%;
    padding: 0 .2rem;
}

.newsletter__input::placeholder {
    color: #343434;
}

/*=============== BUTTONS ===============*/
.button {
    display: inline-block;
    color: #1f1f1fe6;
    background-color: #e4f222;
    padding: .9rem 1rem;
    border-radius: .5rem;
    transition: .3s all;
}

.button:hover {
    background-color: #F6FF76;
}

/*=============== BOTTOM PARAGRAPH ===============*/
.paragraph-wrapper {
    font-weight: 400;
    display: inline-block
}

.paragraph-wrapper,
.paragraph {
    color: #c1c1c198;
}

/*=============== MOBILE NEWLETTER FORM ===============*/
.content {
    display: none;
    place-items: center;
    padding: 0 2em;
    margin-bottom: 1.8em;
}

.mail {
    background-color: #d1d1d1;
    color: #000000;
    padding: 0.5em 0 0.5em 1.5em;
    line-height: 3;
    width: 100%;
    border-radius: 0.5em;
    margin-bottom: 1em;
    margin-top: 1em;
}

.subscribe {
    color: #000000;
    background-color: #e4f222;
    display: inline-block;
    border: none;
    border-radius: 0.5em;
    width: 100%;
    padding: 1em 0;
    transition: .5s all;
}

.subscribe:hover {
    background-color: #F6FF76;
}

.side-imgs-wrapper {
    overflow: hidden;
    position: relative;
    top: -40%;
    display: flex;
    justify-content: space-between;
    gap: 60%;
    align-items: center;
}

.side-imgs-list1 {
    position: relative;
    right: 2%;
    background-color: #787868;
    padding: 1.5em;
    border-top-right-radius: 5%;
    border-bottom-right-radius: 5%;
}

.side-imgs-list2 {
    position: relative;
    right: -5%;
}

.side-imgs img {
    object-fit: cover;
    border-radius: 10px
}

/*=============== MEDIA ===============*/

@media screen and (max-width: 815px) {
    .side-imgs-wrapper {
        display: none;
    }
}

@media (max-width: 700px) {
    .container .hero-container-h1 {
        font-size: 8vw;
    }

    .container .hero-container-paragraph {
        /* font-size: 3vw; */
        padding: 0.5em;
    }
    .paragraph-wrapper,
    .paragraph {
        padding: .5em;
    }
}

@media (max-width: 740px) {
    .section-newsletter {
        display: none;
    }

    .content {
        display: grid;
    }
}


@media screen and (max-width: 576px) {
    .newsletter__container {
        display: grid;
        grid-template-columns: .7fr;
        justify-content: center;
    }

    .newsletter__description {
        padding: 0 3rem;
    }
}
</style>
<template>
    <section class="hero-container">
        <div class="box"></div>
        <div class="container">
            <h1 class="hero-container-h1">Designed to help you save</h1>
            <p class="hero-container-paragraph">Businesses have saved $600M and 8.5M hours with an average savings of 3.5%
                per customer with Ramp.</p>
        </div>
    </section>
    <section class="px-xl-40">
        <div class="feautured-container">
            <div class="feautured-inner">
                <div class="text">
                    <div class="max-w-620">
                        Control your spend on a single platform
                    </div>
                    <div class="btm-text ">
                        Stay in policy and on budget with proactive policy controls, configurable approvals, and
                        AI-powered reconciliation.
                    </div>
                    <button class="button">Platform <img
                            src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/618430895dacc1028c60e007_arrow-right.svg"
                            loading="lazy" alt="" class="cta-arrow-22"></button>
                </div>
                <div class="feauture-img-wrapper">
                    <img src="../../assets/64aa5db2fb7bf4cdf700d57c_Homepage_card_cropped_03.webp" alt="">
                </div>
            </div>
        </div>
        <div class="feautured-container">
            <div class="feautured-inner">
                <div class="text">
                    <div class="max-w-620">
                        Integrate and stay synced
                    </div>
                    <div class="btm-text ">
                        Seamlessly integrate Ramp with your accounting systems and consolidate your finance stack.
                    </div>
                    <button class="button">Integrations <img
                            src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/618430895dacc1028c60e007_arrow-right.svg"
                            loading="lazy" alt="" class="cta-arrow-22">
                    </button>
                </div>
                <div class="feauture-img-wrapper">
                    <img src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/64aa5db2fb7bf4cdf700d58c_Homepage_product%2520graphic_8-p-1600.webp"
                        alt="">
                </div>
            </div>
        </div>
        <div class="feautured-container">
            <div class="feautured-inner">
                <div class="text">
                    <div class="max-w-620">
                        Spend smarter, save every time
                    </div>
                    <div class="btm-text ">
                        Use instant insights to get the best price on software, stop redundant spend before it happens, and
                        make every dollar go further.
                    </div>
                    <button class="button">Intelligence <img
                            src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/618430895dacc1028c60e007_arrow-right.svg"
                            loading="lazy" alt="" class="cta-arrow-22"></button>
                </div>
                <div class="feauture-img-wrapper">
                    <img src="../../assets/64c95defa08ca890cde4f5d3_Homepage_product graphic_11 (1).png" alt="">
                </div>
            </div>
        </div>
        <div class="feautured-container">
            <div class="feautured-inner">
                <div class="text">
                    <div class="max-w-620">
                        Set your team free
                    </div>
                    <div class="btm-text ">
                        Keep everyone focused on the big picture, and let Ramp automate the rest: expenses, accounting,
                        compliance, and more.
                    </div>
                    <button class="button">Accounting automation <img
                            src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/618430895dacc1028c60e007_arrow-right.svg"
                            loading="lazy" alt="" class="cta-arrow-22"></button>
                </div>
                <div class="feauture-img-wrapper">
                    <img src="../../assets/64c95defa08ca890cde4f5d3_Homepage_product graphic_11 (1).png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.hero-container {
    margin-top: 7em;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
}

.container {
    width: 100%;
    max-width: 760px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

.box {
    background-color: #e4f222;
    width: 16px;
    height: 16px;
    border-radius: 4px;
}

.container .hero-container-h1 {
    position: relative;
    z-index: 10;
    letter-spacing: -0.02em;
    font-size: 2.9em;
}

.container .hero-container-paragraph {
    position: relative;
    z-index: 10;
    text-align: center;
    margin: auto;
    max-width: 450px;
}

.px-xl-40 {
    padding: 60px;
    margin-top: 3em;
}

@media (min-width: 1050px) {
    .feautured-container {
        width: 100%;
        max-width: 1440px;
        flex-direction: column;
        margin-left: auto;
        margin-right: auto;
        padding-left: 40px;
        padding-right: 40px;
    }
}

@media (max-width: 750px) {
    .feautured-container {
        padding: 20px;
    }
}

@media (max-width: 550px) {
    .feautured-container {
        padding: 0px;
    }
}

.feautured-inner {
    border-top: 1px solid #7979794d;
    border-bottom: 1px solid #7979794d;
    display: grid;
    grid-column-gap: 16px;
    grid-row-gap: 16px;
    grid-template-rows: auto;
    grid-template-columns: 1.5fr 1fr;
    grid-auto-columns: 1fr;
    padding: 16px;
}

.text {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 32px;
}

.max-w-620 {
    max-width: 330px;
    font-weight: 600;
    font-size: 1.8em;
    margin-bottom: 1em;
}

.btm-text {
    color: #000000;
    font-size: 1.3em;
    max-width: 420px;
    /* font-weight: 500; */
}

.button {
    display: flex;
    align-items: center;
    margin-top: 1em;
    text-align: left;
}

.cta-arrow-22 {
    margin-left: .3em;
    transition: all 0.4s ease-in;
}

.button:hover .cta-arrow-22 {
    transform: translateX(5px);
}

.feauture-img-wrapper {
    width: 100%;
    justify-self: end;
    justify-content: flex-end;
    display: flex;
    align-items: center;
    position: relative;
    overflow: hidden;
}

.feauture-img-wrapper img {
    border-radius: 16px;
}


@media (max-width: 1050px) {
    .px-xl-40 {
        padding: 0px;
    }

    .feautured-inner {
        display: block;
    }

    .text {
        padding: 60px;
    }

    .feauture-img-wrapper {
        display: none;
    }
}

@media (max-width: 750px) {
    .text {
        padding: 0px;
    }
}

@media (max-width: 550px) {
    .text {
        padding: 20px;
    }
}


@media (max-width: 700px) {
    .container .hero-container-h1 {
        font-size: 5vw;
        /* Adjust the font size as needed */
    }

    .container .hero-container-paragraph {
        /* font-size: 3vw; */
        margin-bottom: 2em;
    }
}
</style>

<template>
    <section class="px-xl-40">
        <div class="contain-22 ">
            <div class="feautured-container">
                <div class="feautured-inner">
                    <div class="text">
                        <div class="text-head">
                            <img src="https://assets-global.website-files.com/5f8dd056c51c1d04c3eaa497/64c93e95c8cae35874ce1a21_Shopify_logo_grey.svg"
                                alt="Shopify">
                        </div>
                        <div class="max-w-620">
                            “For day to day users, finance should not be complicated. It should not be something our team is
                            spending their time on. Ramp is so intuitive, people get it right away.”
                        </div>
                        <div class="btm-text">
                            Phil Whitham, Director, International Controller, Shopify
                        </div>
                    </div>
                    <div class="feauture-img-wrapper">
                        <img src="../../assets/64c448da8b8dda8ee1a7fdad_Square_230624_Shopify_CustomerPortrait_07-p-500.jpg"
                            width="400" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.px-xl-40 {
    padding: 60px;
}

.contain-22 {
    width: 100%;
    max-width: 1440px;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    padding-left: 40px;
    padding-right: 40px;
}

.feautured-container {
    color: #fff;
    background-color: #787868;
    border-radius: 16px;
    position: relative;
}

.feautured-inner {
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

.text-head {
    margin-bottom: 3em;
}

.max-w-620 {
    max-width: 620px;
    margin-bottom: 1em;
}

.btm-text {
    color: rgba(255, 255, 255, .7);
}

.feauture-img-wrapper {
    width: 100%;
    justify-self: end;
    justify-content: flex-end;
    display: flex;
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

    .contain-22 {
        padding-left: 0px;
        padding-right: 0px;
    }

    .feautured-container {
        border-radius: 0;
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
        /* padding: 50px; */
    }
}

@media (max-width: 550px) {
    .text {
        padding: 20px;
    }
}
</style>
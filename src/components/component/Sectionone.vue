<template>
    <section class="hero-container">
        <div class="box"></div>
        <div class="container">
            <h1 class="hero-container-h1">The card is just the start</h1>
            <p class="hero-container-paragraph">Everything you need to control spend and optimize finance operations, all on
                a single platform.</p>
        </div>
        <div class="grid-container">
            <div class="grid-item">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Global corporate card</div>
                        <img src="https://assets-global.website-files.com/648a002878c75a4ae9623f12/648a002878c75a4ae96244cc_arrow-right.svg"
                            loading="lazy" id="w-node-_23b0ce91-0f22-427f-01cb-a9501a80d1ba-cdd5b0ab" alt=""
                            class="home-card__arrow">
                    </div>
                    <div class="mt-8 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and
                                full
                                visibility.</div>
                        </div>
                    </div>
                </div>
                <img src="../../assets/64aa5db2fb7bf4cdf700d57c_Homepage_card_cropped_03.webp" alt="" class="image-darken"
                    style="">
            </div>

            <div class="grid-item">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Global corporate card</div>
                        <img src="https://assets-global.website-files.com/648a002878c75a4ae9623f12/648a002878c75a4ae96244cc_arrow-right.svg"
                            loading="lazy" id="w-node-_23b0ce91-0f22-427f-01cb-a9501a80d1ba-cdd5b0ab" alt=""
                            class="home-card__arrow">
                    </div>
                    <div class="mt-8 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and
                                full
                                visibility.</div>
                        </div>
                    </div>
                </div>
                <img src="../../assets/64aa5db2fb7bf4cdf700d5c5_em-top-end.svg" alt="" class="image-darken">
            </div>

            <div class="grid-item">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Global corporate card</div>
                        <img src="https://assets-global.website-files.com/648a002878c75a4ae9623f12/648a002878c75a4ae96244cc_arrow-right.svg"
                            loading="lazy" id="w-node-_23b0ce91-0f22-427f-01cb-a9501a80d1ba-cdd5b0ab" alt=""
                            class="home-card__arrow">
                    </div>
                    <div class="mt-8 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and
                                full
                                visibility.</div>
                        </div>
                    </div>
                </div>
                <img src="../../assets/64aa5db2fb7bf4cdf700d5ad_Ap.svg" alt="" class="ap-end image-darken">
            </div>

            <div class="grid-item">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Global corporate card</div>
                        <img src="https://assets-global.website-files.com/648a002878c75a4ae9623f12/648a002878c75a4ae96244cc_arrow-right.svg"
                            loading="lazy" id="w-node-_23b0ce91-0f22-427f-01cb-a9501a80d1ba-cdd5b0ab" alt=""
                            class="home-card__arrow">
                    </div>
                    <div class="mt-8 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and
                                full
                                visibility.</div>
                        </div>
                    </div>
                </div>
                <img src="../../assets/64aa5db2fb7bf4cdf700d5ab_aa-end.svg" alt="" class="image-darken">
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
    /* height: 30vh; */
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
    max-width: 480px;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    width: 90%;
    margin: 0 auto;
    max-width: 80rem;
    padding: 30px;
    margin-bottom: 5em;
}

.grid-item {
    position: relative;
    overflow: hidden;
    background-color: #f2f2f2;
    z-index: 1;
    height: 100%;
    padding: 32px 24px;
    border-radius: 5%;
    transition: .5s all;
}

.grid-item:hover {
    box-shadow: -1px 20px 52px -30px rgba(0,0,0,0.66);
-webkit-box-shadow: -1px 20px 52px -30px rgba(0,0,0,0.66);
-moz-box-shadow: -1px 20px 52px -30px rgba(0,0,0,0.66);
}

.home-card__heading-wrapper {
    grid-column-gap: 8px;
    grid-template-rows: auto;
    grid-template-columns: 1fr 20px;
    grid-auto-columns: 1fr;
    display: grid;
}

.ap-end {
    padding: 1em;
    position: absolute;
    left: 0%;
    right: 0%;
}

@media (max-width: 1050px) {
    .grid-container {
        grid-template-columns: repeat(2, 1fr);
    }

    .ap-end {
        padding: 0;
        position: relative;
        left: 0%;
        right: 0%;
    }
}

@media (max-width: 550px) {
    .grid-container {
        grid-template-columns: repeat(1, 1fr);
    }

    .grid-container {
        padding: 5px;
    }
}
</style>

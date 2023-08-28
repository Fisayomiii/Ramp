<template>
    <section class="hero-container">
        <div class="box"></div>
        <div class="container">
            <h1 class="hero-container-h1">The card is just the start</h1>
            <p class="hero-container-paragraph">Everything you need to control spend and optimize finance operations, all on
                a single platform.</p>
        </div>
    </section>

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
                        <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and full
                            visibility.</div>
                    </div>
                </div>
            </div>
            <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" alt="" class="image-darken">
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
                        <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and full
                            visibility.</div>
                    </div>
                </div>
            </div>
            <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" alt="" class="image-darken">
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
                        <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and full
                            visibility.</div>
                    </div>
                </div>
            </div>
            <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" alt="" class="image-darken">
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
                        <div class="detail-22">Control your spend globally with unlimited cards, smart policies, and full
                            visibility.</div>
                    </div>
                </div>
            </div>
            <img src="../../assets/64adc5832ad32465eb858c59_Homepage_Hero_01_33.webp" alt="" class="image-darken">
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
    height: 60vh;
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
}

.grid-item {
    background-color: #f2f2f2;
    z-index: 1;
    height: 100%;
    flex-direction: column;
    justify-content: space-between;
    padding: 32px 24px;
    display: flex;
    position: relative;
    overflow: hidden;
}


.home-card__heading-wrapper {
    grid-column-gap: 8px;
    grid-template-rows: auto;
    grid-template-columns: 1fr 20px;
    grid-auto-columns: 1fr;
    display: grid;
}

@media (max-width: 1050px) {
    .grid-container {
        grid-template-columns: repeat(2, 1fr);
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

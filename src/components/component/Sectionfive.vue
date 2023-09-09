<template>
    <section class="hero-container">
        <div class="box"></div>
        <div class="container">
            <h1 class="hero-container-h1">Built to scale globally</h1>
            <p class="hero-container-paragraph">Whether you’re building your business, expanding internationally, or cutting
                costs—Ramp works for you.</p>
        </div>

        <div class="grid-container">

            <div class="grid-item">
                <img src="../../assets/64c95defa08ca890cde4f5d3_Homepage_product graphic_11 (1).png" alt=""
                    class="image-darken">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Completely flexible</div>
                    </div>
                    <div class="mt-3 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Customize Ramp to fit your business and give you the controls you need with policies, roles, and approval workflows.</div>
                        </div>
                    </div>
                </div>

            </div>

            <div class="grid-item">
                <img src="../../assets/64c95defa08ca890cde4f5d3_Homepage_product graphic_11 (1).png" alt=""
                    class="image-darken">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">Works where you work</div>
                    </div>
                    <div class="mt-3 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Send payments to 195 countries in over 40 currencies and reimburse employees in their local currencies within two days.</div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="grid-item">
                <img src="../../assets/64c95df07c3fe416aa8f8dae_Homepage_product graphic_12 (1).png" alt=""
                    class="image-darken">
                <div class="image-container">
                    <div class="home-card__heading-wrapper">
                        <div class="home-card__heading">An extension of your team</div>
                    </div>
                    <div class="mt-3 mb-5">
                        <div class="text-color black-700">
                            <div class="detail-22">Get dedicated support anytime, anywhere. We’re always ready to help.</div>
                        </div>
                    </div>
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
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    width: 100%;
    margin: 0 auto;
    max-width: 75rem;
    padding: 30px;
    margin-bottom: 5em;
}

.grid-item {
    position: relative;
    overflow: hidden;
    z-index: 1;
    height: 100%;
    padding: 32px 24px;
    border-radius: 5%;
    transition: .5s all;
}

.image-darken {
    border-radius: 10px;
    margin-bottom: 2em;
}

.home-card__heading-wrapper {
    font-weight: 600;
    font-size: 1.2em;
}

@media (max-width: 1050px) {
    .grid-container {
        grid-template-columns: repeat(2, 1fr);
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

@media (max-width: 550px) {
    .grid-container {
        grid-template-columns: repeat(1, 1fr);
    }

    .grid-container {
        padding: 30px;
    }
}</style>

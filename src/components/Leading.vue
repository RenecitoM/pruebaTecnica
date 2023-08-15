<template>
    <div class="split-screen">
        <div class="left-panel">
            <div class="text-container">
                <h2 class="title-center">{{ "Leading Edge Technology" }}</h2>
                <p class="text-start">{{ "Easy to use management tools, our fastest possible execution and spreads as lowas 0.0." }}</p>
                <p class="text-a">{{ "Quick Guide: CommuniTraders Web User Manual" }}</p>
            </div>
        </div>
        <div class="right-panel">
            <v-container fluid>
                <img src="./assets/Mask Group 2.png" alt="" class="img" />
            </v-container>
        </div>
    </div>
</template>

<style>
:root {
    ---c1c3c9: #c1c3c9;
    ---e2e2e2: #e2e2e2;
    ---6e7079: #6e7079;
    ---363636: #363636;
    ---f2f2f2: #f2f2f2;
    ---3c3e48: #3c3e48;
    ---a51c20: #a51c20;
    ---ff0000: #ff0000;

    --unnamed-font-family-noto-sans: Noto Sans;
    --unnamed-font-style-normal: normal;
    --unnamed-font-weight-300: 300px;
    --unnamed-font-weight-900: 900px;
    --unnamed-font-weight-normal: normal;
    --unnamed-font-size-25: 25px;
    --unnamed-font-size-30: 30px;
    --unnamed-font-size-32: 32px;
    --unnamed-font-size-45: 45px;
    --unnamed-character-spacing-0: 0px;
    --unnamed-line-spacing-36: 36px;
    --unnamed-line-spacing-43: 43px;
    --unnamed-line-spacing-45: 45px;
    --unnamed-line-spacing-64: 64px;
}

.split-screen {
    display: flex;
    width: 100%;
    height: 70vh;
}

.left-panel {
    flex: 1;
    display: block;
    justify-content: start;
    background-color: #f5f5f5;
    padding-top: 15%;
    padding-left: 15%;
}

.right-panel {
    flex: 1;
    display: flex;
    justify-content: center;
    padding-top: 5%;
    background-color: #f5f5f5;
}

.right-panel img {
    max-width: 100%;
    max-height: 80vh;
}

.tittle-center {
    top: 2106px;
    left: 343px;
    width: 516px;
    height: 49px;
    text-align: left;
    font: normal normal 900 30px/45px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    opacity: 1;
    display: block;
}

.text-start {
    top: 2177px;
    left: 343px;
    width: 556px;
    height: 85px;
    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-normal) var(--unnamed-font-size-25)/var(--unnamed-line-spacing-36) var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    color: var(---363636);
    text-align: left;
    font: normal normal normal 25px/36px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    opacity: 1;
    margin-top: 3%;
}

.text-a {
    top: 2177px;
    left: 343px;
    width: 556px;
    height: 50px;
    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-normal) var(--unnamed-font-size-25)/var(--unnamed-line-spacing-36) var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    color: var(---363636);
    text-align: left;
    font: normal normal normal 18px/36px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    opacity: 1;
    margin-top: 3%;
    text-decoration: underline;
}
</style>

<script>
export default {
    props: {
        leftText: String,
        imageSrc: String,
    },
};
</script>
<template>
    <header class="header">
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <div class="logo-left col-3 col-md-2">
                    <img src="./assets/Logo.png" alt="" class="navbar-brand" />
                </div>
                <div class="col-6 col-md-5">
                    <nav class="nav d-flex justify-content-start">
                        <div class="nav-item m-3 col-3 col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3">
                            FOREX
                        </div>
                        <div class="nav-item m-3 col-3 col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3">
                            STOCKS
                        </div>
                        <div class="nav-item m-3 col-3 col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3">
                            FUTURES
                        </div>
                        <div class="nav-item m-3 col-3 col-xs-3 col-sm-3 col-md-3 col-lg-3 col-xl-3">
                            TradeGATEHub
                        </div>
                    </nav>
                </div>
                <div class="d-flex align-items-center col-3 col-md-2">
                    <div class="login">Log in</div>
                    <div class="contact">| Contact us</div>
                    <div class="contact">
                        English
                        <v-container fluid>
                            <img src="./assets/world-wide-web.png" alt="" class="icon" />
                        </v-container>
                    </div>
                </div>
            </div>

            <div class="col-12 mt-3">
                <div class="secondList col-1 col-xs-1 col-sm-1 col-md-1 col-lg-1 col-xl-1 mx-3">
                    Markets
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Company ᵛ
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Accounts
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Platforms ᵛ
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Pricing
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Introducing Brokers
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Education
                </div>
                <div class="secondList m-3 col-2 col-xs-2 col-sm-2 col-md-2 col-lg-2 col-xl-2">
                    Support ᵛ
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped>
@font-face {
    font-family: "Noto Sans";
    src: url("Noto_Sans/NotoSans-Black.ttf");
    src: url("Noto_Sans/NotoSans-Light.ttf");
}

.header {
    background-color: #181f29;
    color: #fff;
}

.container {
    max-width: 100%;
    margin: 0;
}

.logo-left {
    margin: 1%;
    display: inline-block;
}

.split-container {
    display: flex;
    height: 100vh;
}

.left-side {
    width: 45%;
    background: linear-gradient(to bottom, rgba(24, 31, 41, 1), rgba(24, 31, 41, 0));
    /* Ajusta los valores según necesites */
}

.right-side {
    width: 55%;
    background-color: #f2f2f2;
}

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

.h2 {
    font-family: var(--unnamed-font-family-noto-sans);
    font-style: var(--unnamed-font-style-normal);
    font-weight: var(--unnamed-font-weight-900);
    font-size: 17px;
    line-height: var(--unnamed-line-spacing-45);
    letter-spacing: var(--unnamed-character-spacing-0);
    color: #fff;
}

.h1 {
    font-family: var(--unnamed-font-family-noto-sans);
    font-style: var(--unnamed-font-style-normal);
    font-weight: var(--unnamed-font-weight-900);
    font-size: var(--unnamed-font-size-45);
    line-height: var(--unnamed-line-spacing-64);
    letter-spacing: var(--unnamed-character-spacing-0);
    color: var(---363636);
}

.nav-item {
    top: 49px;
    left: 555px;
    width: 55px;
    height: 22px;
    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-900) 2px/22px var(--unnamed-font-family-noto-sans);
    text-align: left;
    font: normal normal 900 14px/22px Noto Sans;
    letter-spacing: 4.8px;
    color: #ffffff;
    text-transform: uppercase;
    opacity: 1;
    padding-left: 12%;
    display: inline-block;
}

.login {
    top: 50px;
    left: 1461px;
    width: 47px;
    height: 12px;
    font: var(--unnamed-font-style-normal) normal medium 16px/22px var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: right;
    font: normal normal medium 16px/22px Noto Sans;
    letter-spacing: 0px;
    color: #c1c3c9;
    opacity: 1;
    display: inline-block;
}

.contact {
    top: 50px;
    left: 1461px;
    width: 87px;
    height: 12px;
    font: var(--unnamed-font-style-normal) normal medium 16px/22px var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: right;
    font: normal normal medium 16px/22px Noto Sans;
    letter-spacing: 0px;
    color: #6e7079;
    opacity: 1;
    display: inline-block;
}

.secondList {
    width: auto;
    height: 12px;
    font: var(--unnamed-font-style-normal) normal medium 16px/22px var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: right;
    font: normal normal medium 16px/22px Noto Sans;
    letter-spacing: 0px;
    color: #c1c3c9;
    opacity: 1;
    display: inline-block;
    padding-right: 4%;
    padding-bottom: 1%;
}

.icon {
    height: 1em;
    color: #f2f2f2;
}

.arrow {
    width: 40px;
    height: 40px;
    top: 50%;
    margin: -20px 0 0 -20px;
    border-left: none;
    border-top: none;
    border-right: 2px #fff solid;
    border-bottom: 2px #fff solid;
}
</style>
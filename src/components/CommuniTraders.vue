<template>
    <div class="split-screen">
        <div class="center-panel">
            <div class="text-container">
                <h2 class="SubTittle">{{ "Try CommuniTraders Now!" }}</h2>
            </div>
            <div class="contenedor-footer col-12 col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
                <div class="Broker">
                    <p class="sub-text col-4">Free Download for Tradeview Users</p>
                    <button class="transparent-button row-1">Contact your Broker</button>
                </div>
                <div class="Tradeview">
                    <p class="sub-text col-4">Don’t have a Tradeview Account yet?</p>
                    <button class="red-button row-1">Get a Free Demo</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.transparent-button {
    background-color: transparent;
    border: 2px solid #fff;
    color: #fff;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
    margin-left: 3em;
    margin-top: 3em;
}

.contenedor-footer {
    display: flex;
    justify-content: space-between;

}

.red-button {
    background-color: #ff0000;
    color: #fff;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
    margin-top: 3em;
    margin-left: 4em;
}

.vertical-line {
    width: 1em;
    background-color: #ccc;
}

.split-screen {
    display: flex;
    width: 100%;
    height: 60vh;
    background-color: #181F29;
}

.center-panel {
    margin-top: 5%;
    margin-left: 35%
}

.SubTittle {
    top: 2590px;
    left: 756px;
    width: 408px;
    height: 41px;
    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-900) var(--unnamed-font-size-30)/var(--unnamed-line-spacing-45) var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: start;
    font: normal normal 900 30px/45px Noto Sans;
    letter-spacing: 0px;
    color: #FFFFFF;
    opacity: 1;
    margin-left: 15%;
}

.sub-text {
    top: 2709px;
    left: 574px;
    width: 300px;
    height: 24px;
    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: start;
    font: normal normal 300 18px/24px Noto Sans;
    letter-spacing: 0px;
    color: #FFFFFF;
    opacity: 1;
    padding-top: 15%;
}
</style>
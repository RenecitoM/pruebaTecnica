<template>
  <div class="split-container col-12">
    <div class="left-side"></div>
    <div class="right-side">
      <div class="container-img">
        <v-container fluid>
          <img src="./assets/Group302x.png" alt="" class="icono" />
        </v-container>
      </div>
      <div class="line"></div>
      <h2 class="parrafo">
        Tradeview’s
        <b class="b">CommuniTraders</b>
        software lets our partners provide value-added copy trading to their
        clients.
      </h2>
      <div class="contenedor-footer col-12 col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <div class="Broker">
          <p class="asideText col-4">Free Download for Tradeview Users</p>
          <button class="transparent-button row-1">Contact your Broker</button>
        </div>
        <div class="Tradeview">
          <p class="asideText2 col-4">Don’t have a Tradeview Account yet?</p>
          <button class="red-button row-1">Get a Free Demo</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
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

.split-container {
  display: flex;
  height: 85vh;
}
.left-side {
  width: 45%;
  height: 100%;
  background-image: url("./assets/backPage.png");
  background-size: 100%;
  background-position: center;
}

.right-side {
  width: 55%;
  background-color: #181f29;
}

.icono {
  width: 20em;
}

.container-img {
  margin-left: 32%;
  margin-top: 15%;
}

.line {
  width: 62%;
  height: 1px;
  background-color: #fff;
  margin-left: 21%;
  margin-top: 7%;
}

.parrafo {
  top: 0px;
  left: 9px;
  height: 43px;
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) var(--unnamed-font-size-32) / var(--unnamed-line-spacing-43) var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 24px/43px Noto Sans, Light;
  letter-spacing: 0px;
  color: #ffffff;
  width: 50%;
  margin-left: 25%;
  margin-bottom: 17%;
}

.b {
  top: 0px;
  left: 181px;
  width: 282px;
  height: 43px;
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-900) 16px/22px var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 900 32px/43px Noto Sans, Blank;
  letter-spacing: 0px;
  color: #ffffff;
}

.Broker {
  margin-left: 15%;
  display: inline;
}

.asideText {
  top: 783px;
  width: 200px;
  height: 24px;
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 18px/24px Noto Sans;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
  display: inline;  
  margin: 0;
  padding: 0;
}

.asideText2 {
  top: 783px;
  width: 100px;
  height: 24px;
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 18px/24px Noto Sans;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
  display: inline;  
  margin: 0;
  padding: 0;
}

.transparent-button {
  background-color: transparent;
  border: 2px solid #fff;
  color: #fff;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
  margin-left: 3em;
  margin-top: 1em;
}

.red-button {
  background-color: #ff0000;
  color: #fff;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
  margin-top: 1em;
  margin-left: 4em;
}

.contenedor-footer{
  display: flex;
  justify-content: space-between;
}
</style>

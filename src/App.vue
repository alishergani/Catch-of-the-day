<template>
  <div id="app">
  	<router-view></router-view>
  </div>
</template>

<style lang="scss">
* {
	padding: 0;
	margin: 0;
	box-sizing: border-box;
}
::-webkit-scrollbar {
    width: 0px;
    background: transparent;
}

@font-face {
  font-family: "haymakerregular";
  src: url("./assets/fonts/haymaker-webfont.eot");
  src: url("./assets/fonts/haymaker-webfont.eot?#iefix") format("embedded-opentype"), 
  url("./assets/fonts/haymaker-webfont.woff") format("woff"), 
  url("./assets/fonts/haymaker-webfont.ttf") format("truetype"), 
  url("./assets/fonts/haymaker-webfont.svg#haymakerregular") format("svg");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'blanchcaps_inline';
  src: url('./assets/fonts/blanch_caps_inline-webfont.eot');
  src: url('./assets/fonts/blanch_caps_inline-webfont.eot?#iefix') format('embedded-opentype'),
       url('./assets/fonts/blanch_caps_inline-webfont.woff') format('woff'),
       url('./assets/fonts/blanch_caps_inline-webfont.ttf') format('truetype'),
       url('./assets/fonts/blanch_caps_inline-webfont.svg#blanchcaps_inline') format('svg');
  font-weight: normal;
  font-style: normal;
}
body {
	background-color: #d4d4d4;
}
#app {
	width: 100%;
	height: 100vh;
}
</style>

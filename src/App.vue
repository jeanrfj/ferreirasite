<template>

  <div>
    <HeaderComponent />
    <BannerComponent />
    <MainComponent />
    <FooterComponent />
  </div>


</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import BannerComponent from './components/BannerComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {

  name: 'App',
  components: {
    HeaderComponent,
    BannerComponent,
    MainComponent,
    FooterComponent
  }

}
</script>

<style>
#app {
  font-family: 'Quicksand', sans-serif;
  box-sizing: border-box;
  color: #3e4346;
}

html,
body {

  height: 100%;
  widows: 100%;
}

html,
body,
div,
span,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
pre,
a,
img,
small,
strong,
tt,
b,
i,
center,
ol,
ul,
li,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
section {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
  box-sizing: border-box;
}


article,
aside,
details,
figcaption,
figure,
footer,
header,
menu,
nav,
section {
  display: block;
}

body {
  line-height: 1;
}

ol,
ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}

a,
a:visited {
  text-decoration: none;
  color: inherit;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

.d-flex-column {
  display: flex;
  flex-flow: column;
}

.d-flex-row {
  display: flex;
}

.d-flex-row {
  display: flex;
  flex-flow: row wrap;
}

.wrap {
  flex-wrap: wrap;
}

.j-center {
  justify-content: center;
}

.a-center {
  align-items: center;
}
</style>

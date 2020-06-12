<template lang="pug">
  div.main-wrape
      div.container 
        div 
          logo
          h1.title NUXT-UNIV-STARTER
          //- h1.title NUXT-CSS-LAYOUT 
          //- h2.subtitle Nuxt project css layout starter
          //-     div 1. HOME
          //-     div 2. EXPROLER
          //-     div 3. LAYOUT
          //-     div 4. NAVIGATION
          //-     div 5. INPUT
          //-     div 6. DISPLAY
          //-     div 7. FEEDBACK

          div.rem size 1.6rem = 16px
          div.pxs size  16px = 1.6rem
          div.em size 1.6em = 16px
           
          div.rem-box 
            p 10rem box 
          div.px-box 
            p 100px box

          div.rem10 size 10rem
          div.px100 size 100px
          h1 h1 令和2年 
          h2 h2 令和2年 
          h3 h3 令和2年
          h4 h4 令和2年
          h5 h5 令和2年
          h6 h6 令和2年
          div.h7 div.h7令和2年
          p p 令和2年
      
</template>
<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scope lang="scss">
// * {
//   border: 1px solid $grey-lighter;
// }
.rem10 {
  font-size: 10rem;
  color: $blue;
}
.px100 {
  font-size: 100px;
  color: $red;
}

.rem-box {
  font-size: 10rem;
  width: 50rem;
  height: 20rem;
  background-color: $blue;
}
.px-box {
  font-size: 100px;
  width: 500px;
  height: 200px;
  background-color: $red;
}

.rem {
  font-size: 1.6rem;
  color: $blue;
}
.pxs {
  font-size: 16px;
  color: $red;
}

.em {
  font-size: 1.6em;
  color: $purple;
}
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>

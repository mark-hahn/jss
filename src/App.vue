<template lang="pug">
div
  #hdr(style=`border: 2px solid black; width:100%;
              position: fixed; left: 0; top: 0;
              background-color:yellow`)
    div(style=`padding:0 1em; width:100%; display:flex;`)
      div(style=`font-weight:bold; font-size:1.5em;
                  flex-basis:2.5em;`) SSJ
      input(v-model="topExpr" @input="select"
            style=`border:1.5px solid black; height:1.5em;
                   font-size:1.2em; flex-grow:1; margin-top:.25em;`)
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'

export default {
  name: "App",
  
  components: { },

  data() {
  },

  methods: {
  }
}

</script>

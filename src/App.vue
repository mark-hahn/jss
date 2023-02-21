<template lang="pug">
div
  #hdr(style=`border: 2px solid black; width:100%;
              position: fixed; left: 0; top: 0;
              background-color:yellow`)
    div(style=`margin:0 1em; display:inline-block; width:100%;
              display:flex;`)
      #lbl(style=`font-weight:bold; font-size:1.5em;
                  flex-basis:5em;`) JSS
      input(v-model="topExpr" @input="select"
            style=`border:2px solid black;
                  position:relative; bottom:.15em;
                  font-size:1.2em;
                  flex-grow:1;`)
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'


</script>

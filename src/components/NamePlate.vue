<template>
  <div id="namePlate" class="centerStageText namePlate">
    MIGUEL <u>ALEX</u> CANTU
  </div>
</template>


<script>
export default {
  name: 'nameplate',
  data: function () {
    return {
    }
  },
  created () { },
  methods: {
    async setup () {
    },
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Staatliches&display=swap');

.namePlate {
  margin-bottom: 15px;
  font-family: 'Staatliches', cursive;
  font-size: 40px;
  letter-spacing: 2px;
  word-spacing: 2px;
  color: #57624D;
  color: #FFFFFF;
  font-weight: normal;
  text-decoration: none;
  font-style: normal;
  font-variant: normal;
  text-transform: uppercase;
  -webkit-text-stroke: .75px black;
	transition: .5s ease-in-out;
}

.namePlate:hover {
  letter-spacing: 4px;
}
</style>

<template>
  <div id="app">
    <!-- <router-view></router-view> -->
    <div class='container'>
      <span v-for="(items,i) in 60" class='light' v-bind:class=""></span>
    </div>
    <div v-for>
        
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data(){
    return {
      msg : [
        ['1','one'],
        ['2','two'],
        ['3','three']
      ]
    }
  }
}
</script>

<style>
body {
  margin: 0;
  overflow: hidden;
  text-align: center;
  background:#000;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container {
  width: 80%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.light:nth-child(1) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.15s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf63;
}

.light:nth-child(2) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.825s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf9c40;
}

.light:nth-child(3) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.71s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #7840bf;
}

.light:nth-child(4) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.74s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf9c40;
}

.light:nth-child(5) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.515s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #9640bf;
}

.light:nth-child(6) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.675s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf4057;
}

.light:nth-child(7) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.515s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #59bf40;
}

.light:nth-child(8) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.855s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #407abf;
}

.light:nth-child(9) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.435s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf54;
}

.light:nth-child(10) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.735s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #8f40bf;
}

.light:nth-child(11) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.695s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #87bf40;
}

.light:nth-child(12) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.455s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #404dbf;
}

.light:nth-child(13) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.955s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #6140bf;
}

.light:nth-child(14) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.675s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #6140bf;
}

.light:nth-child(15) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.955s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #4091bf;
}

.light:nth-child(16) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.125s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40b8bf;
}

.light:nth-child(17) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.765s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #4099bf;
}

.light:nth-child(18) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.79s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #96bf40;
}

.light:nth-child(19) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.195s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #61bf40;
}

.light:nth-child(20) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.175s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #4082bf;
}

.light:nth-child(21) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.9s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #8740bf;
}

.light:nth-child(22) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.985s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf7d40;
}

.light:nth-child(23) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.33s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf6640;
}

.light:nth-child(24) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.205s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bfb0;
}

.light:nth-child(25) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.67s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bfa8;
}

.light:nth-child(26) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.27s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf4047;
}

.light:nth-child(27) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.05s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40b8bf;
}

.light:nth-child(28) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.09s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40a8bf;
}

.light:nth-child(29) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.015s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf8540;
}

.light:nth-child(30) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.955s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf7540;
}

.light:nth-child(31) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.105s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf8a;
}

.light:nth-child(32) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.995s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bd40bf;
}

.light:nth-child(33) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.045s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf4066;
}

.light:nth-child(34) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.915s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #6140bf;
}

.light:nth-child(35) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.195s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40a8bf;
}

.light:nth-child(36) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.75s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf409c;
}

.light:nth-child(37) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.315s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #9e40bf;
}

.light:nth-child(38) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.32s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #52bf40;
}

.light:nth-child(39) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.945s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #4240bf;
}

.light:nth-child(40) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.465s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #8fbf40;
}

.light:nth-child(41) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.64s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf4040;
}

.light:nth-child(42) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.69s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #a640bf;
}

.light:nth-child(43) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.635s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf45;
}

.light:nth-child(44) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf99;
}

.light:nth-child(45) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.48s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf4740;
}

.light:nth-child(46) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.185s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bfba40;
}

.light:nth-child(47) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.545s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #59bf40;
}

.light:nth-child(48) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.985s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bfb340;
}

.light:nth-child(49) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.545s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #9ebf40;
}

.light:nth-child(50) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.805s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf4d;
}

.light:nth-child(51) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 3.305s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #40bf6b;
}

.light:nth-child(52) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.18s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf405e;
}

.light:nth-child(53) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.95s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #52bf40;
}

.light:nth-child(54) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.465s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #8740bf;
}

.light:nth-child(55) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 0.345s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #87bf40;
}

.light:nth-child(56) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.6s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #8040bf;
}

.light:nth-child(57) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.02s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #5940bf;
}

.light:nth-child(58) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 4.845s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #bf40ab;
}

.light:nth-child(59) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 1.205s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #5240bf;
}

.light:nth-child(60) {
  position: relative;
  display: inline-block;
  width: 0;
  height: 0;
  margin: 30px;
  background-color: rgba(255, 255, 255, 0);
  opacity: 0;
  animation: light 4s linear infinite;
  animation-delay: 2.905s;
  border-radius: 50%;
  box-shadow: 0 0 40px 20px rgba(255, 255, 255, 0.5), 0 0 50px 40px #69bf40;
}

@keyframes light {
  0% {
    opacity: 0;
  }
  30% {
    opacity: 0.5;
  }
  70% {
    opacity: 0;
  }
}

</style>

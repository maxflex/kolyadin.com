<template>
  <a class='wrapper' href='https://vk.com/mkolyadin' target='_blank'>
    <svg version="1.1" id="logo-inner" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
       x="0px" y="0px" width="239.682px" height="233.884px" viewBox="0 0 239.682 233.884" enable-background="new 0 0 239.682 233.884"
       xml:space="preserve">
    <g>
      <path id='inner-path' fill-rule="evenodd" clip-rule="evenodd" fill="#f44280" d="M219.446,91.352
        c-8.815-3.921-2.929-14.688-8.391-24.676c-6.421-11.743-8.589-2.264-16.83-18.065c-6.864-13.161-11.354-7.242-21.087-14.046
        c-3.27-2.286-6.938-5.929-10.811-7.221c-9.117-3.041-4.282-1.22-9.04-7.84c-7.786-0.546-4.288,0.768-9.982,2.034
        c-4.311-2.608-3.343-5.491-10.96-5.288c-5.755,0.154-3.375,1.107-15.104,0.977c-13.752-0.153,2.283,4.419-26.03,5.077
        c-3.508,6.482-6.458,7.789-15.834,8.143c-3.738,8.309-12.867,7.331-21.776,19.282c-4.261,5.717-1.081-0.831-9.181,10.833
        c-3.102,4.467-6.532,6.994-9.318,10.67c-8.017,10.58-6,23.144-9.519,30.485c-6.653,13.876-2.588,18.687-0.871,24.262
        c1.082,3.513,0.157,5.333,1.469,8.937c4.808,2.237,6.555,0.793,10.321,2.288c1.456,4.326-3.227,4.489-5.842,8.859l8.532,1.468
        c-0.439,6.999-4.687,2.631-3.966,12.901c2.869,3.947,2.643,0.817,3.837,5.138c1.298,4.697,2.157,10.602,9.542,16.602
        c6.383,5.186,7.07,2.672,9.663,7.281c2.311,4.108,2.843,6.856,7.076,9.918c8.247,5.964,15.657,3.835,20.352,6.66l11.147,5.919
        c12.633,7.474,10.159,4.189,17.504,1.573l4.958,2.852c8.199-6.336,2.416-4.834,14.078-2.02c12.963,3.129,4.958,1.631,14.151-2.657
        c3.604-1.682,4.335-0.983,7.718-3.329c3.916-2.717,2.36-3.174,7.095-3.82c5.499-0.751,4.312-0.275,9.081-1.99
        c3.062-1.101,4.52-1.842,6.925-3.075c4.651-2.387,10.694-4.509,13.127-8.92c3.157-5.727,1.662-9.37,7.717-13.236
        c8.095-5.169,6.183-2.003,11.33-10.761c4.05-6.89,4.03-7.342,3.841-17.056c2.261-1.473,4.268-2.127,6.04-4.077
        c-0.613-4.039-2.165-4.574-3.957-7.001c2.38-4.285,3.768-3.186,6.704-6.905c-1.197-5.674-4.198-4.142-1.914-9.104
        c2.747-5.966,2.92-2.113,0.991-9.84c-1.327-5.312,1.721-3.737-1.081-9.893C218.762,97.438,219.348,98.478,219.446,91.352z"/>
    </g>
    </svg>
    <img id='logo-circle' src='/static/img/svg/logo-circle.svg'>
  </a>
</template>

<script>
import Nav from '@/components/Nav'

export default {
  name: 'hello',
  components: { Nav },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang='scss' scoped>
  .wrapper {
    height: 100%;
    width: 100%;
    /*display: flex;
    justify-content: center;
    align-items: center;*/
    & > * {
      position: absolute;
      top: calc(50% - 117px);
      left: calc(50% - 120px);
    }
    & #logo-inner {
      -webkit-animation: spin 100s ease infinite;
      -moz-animation: spin 100s ease infinite;
      animation: spin 100s ease infinite;
    }
    & #logo-circle {
      -webkit-animation: spin-backwards 75s linear infinite;
      -moz-animation: spin-backwards 75s linear infinite;
      animation: spin-backwards 75s linear infinite;
    }
    & #inner-path {
      -webkit-animation: innerpath 100s linear infinite;
      -moz-animation: innerpath 100s linear infinite;
      animation: innerpath 100s linear infinite;
    }
  }
</style>

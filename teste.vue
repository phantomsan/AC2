new Vue({
  el: '#app',
  data: {
    number1: 0,
    number2: 0,
  },
  computed: {
  	result() {
    	return parseInt(this.number1) + parseInt(this.number2);
    }
  }
});
Vue.component('component-a', {
	template: '<div class="input_box"><div class="input_name input"><span>Имя</span><input type="text"></div><div class="input_old_years input"><span>Возраст</span><input type="text"></div><div class="delete"><span>Удалить</span></div></div>'
})

new Vue({
  el: "#app",
  data: {
  	arr: []
    },
    methods: {
    	add(){
      	this.arr.push({
          
        });
        
      }
    }
})
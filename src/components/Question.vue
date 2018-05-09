<template>

<div class="content">

		<button class="btn_header content" @click='toggle()'>Q: {{q}}</button>
		<span v-show="isOpen"> A: {{a}}</span>
						
</div>
  
</template>

<script>
	export default { 

		props: ['q', 'a'],

		data() {
			return {
			isOpen: false
			}
		},

		methods:{
        toggle: function(){
            this.isOpen = !this.isOpen
        }
    },			
}


</script>

<style>




</style>
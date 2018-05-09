<template>

<div class="content">

		<span class="header content" @click='toggle()'>Q: {{q}}</span>
		<br>
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
<template>

<div>
<question v-for="pair in pairs" :q="pair.q" :a="pair.a"> </question>

 	
</div>
</template>

<script>

import Question from './components/Question.vue';

export default {

  name: 'app',
  
  components: { Question}, 

   data () 
   { return {pairs: [
   	{q:'What is always coming, but never arrives?', a:'Tomorrow'},
   	{q:'What is it that lives if it is fed, and dies if you give it a drink?', a:'Fire'},
   	{q:'What do you call a woman who knows where her husband is all the time?', a:'A widow'},
   	{q:'What goes up and down, but always remains in the same place?', a:'Stairs'},
   	{q:'What is it that goes up, but never comes down?', a:'Age'},
   	{q:'What is the biggest problem with snow boots?', a:'Snow boots melt'},
   	{q:'What becomes wetter the more it dries?', a:'A towel'},
   	{q:'What happens if you throw a white hat into the Black Sea?', a:'The hat gets wet.'},
   	{q:'How can a woman go eight days without sleep?', a:'She sleeps at night.'},
   	{q:'If a rooster lays an egg on top of the barn roof, which way will it roll?', a:'It will not roll, because roosters do not lay eggs.'},
   	{q:'How much dirt is there in a hole that is 3 feet deep, 6 feet long, and 4 feet wide?', a:'None, because a hole does not have any dirt inside.'},
   	{q:'What can you never eat for breakfast?', a:'Lunch or dinner'},
   	{q:' If ten birds are sitting in a tree and a hunter shoots one, how birds many are left in the tree?', a:'None, because after one bird got shot, the rest flew away.'},
   	{q:'What is it that stands up, but grows down?', a:'A candle'},
   	{q:'How far can a rabbit run into the woods?', a:'Halfway. After that, he is running out of the woods.'},
   	{q:'Which is heavier? A pound of feathers or a pound of rocks?', a:'Neither. Both weigh a pound!'},
   	{q:'When you have me, you immediately feel like sharing me. But, if you do share me, you do not have me.', a:'A secret'},
   	{q:'Your parents have six sons including you and each son has one sister. How many people are in the family?', a:'Nine. Two parents, six sons, and one daughter.' },
   	{q:'What makes more as you take them?', a:'Footsteps'},
   	{q:'What has a neck but no head?', a:'A bottle'},
   	{q:'What has to be broken before you can use it?', a:'An egg'},
   	{q:'What can you hold without ever touching or using your hands?', a:'Your breath!'},
   	{q:'Which came first: the chicken or the egg?', a:'GOTCHA!'}]
 
  }}
}

 

</script>


<style>

</style>

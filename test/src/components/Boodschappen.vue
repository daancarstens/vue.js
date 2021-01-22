<template>
 <div>
     <div v-bind:key="boodschap.id" v-for="boodschap in boodschappen" >
         <BoodschapItem v-bind:boodschap="boodschap" v-on:del-boodschap="$emit('del-boodschap', boodschap.id)"/>
     </div>
 </div>
</template>

<script>
import BoodschapItem from './Boodschapitem.vue';

 export default {
     name: "Boodschappen",
     components: {
         BoodschapItem
     },
     props: ["boodschappen"]
}
</script>

<style scoped>

</style>
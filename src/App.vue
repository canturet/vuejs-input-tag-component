<template>
 <div class="container">
   <app-tags v-model="tags" color="success"></app-tags>
   <app-tags v-model="tags2" color="danger"></app-tags>
   <app-tags v-model="tags2" color="info"></app-tags>
   <app-tags v-model="tags2" color="primary"></app-tags>
   <app-tags v-model="tags2" color="warning"></app-tags>
   <app-tags v-model="tags2" color="secondary"></app-tags>

 </div>
</template>

<script>
import Tags from "./components/Tags"
export default {
  components : {
    appTags : Tags
  },
  data(){
    return {
      tags : "test1,test2,test3",
      tags2 : "deneme1,deneme2,deneme3"
    }
  }
};
</script>

<style>
body {
  font-family: sans-serif;
}


</style>

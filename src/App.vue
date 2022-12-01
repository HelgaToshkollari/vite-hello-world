<script>
import AppTitle from "./components/AppTitle.vue"

export default {
	components: { AppTitle },
  data(){
    return{
      title: "La mia prima app con Vite!"
    };
  },
  methods: {
    fetchData(){

    }
  }
  
};
</script>

<template>

	<AppTitle></AppTitle>
	
	
</template>
<style></style>
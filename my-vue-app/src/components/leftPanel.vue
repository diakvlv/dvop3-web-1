<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>


<template>
  <div class="container">
	   <div class="column1">
      <table>
        <tr>
          <td><h2><b>Cuacane</b></h2></td>
        </tr>
        <tr>
          <td>Dashboard</td>
        </tr>
        <tr>
        <td>Map</td>
        </tr>
        <tr>
        <td>Saved Location</td>
        </tr>
        <tr>
        <td>Calendar</td>
        </tr>
        <tr>
        <td>Settings</td>
        </tr> 
        <tr>
        <td valign="bottom">Log out</td>
        </tr>
        </table>    
	   </div>
  </div>
</template>

<style scoped>
*

template {
  margin: 0;
  padding: 0;
}
.column1 {
	  width: 20%;
	  background-color:aqua;
	  text-align: left;
    float: left;
    margin-left:0%;
    position:absolute;
    top:0px;
    right:0px;
    bottom:0px;
    left:0px;
	}

</style>

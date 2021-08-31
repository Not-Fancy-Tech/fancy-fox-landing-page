<template>
    <div class="scene">
      <div class="wrap">
        <div class="wall wall-right"></div>
        <div class="wall wall-left"></div>
        <div class="wall wall-top"></div>
        <div class="wall wall-bottom"></div>
        <div class="wall wall-back"></div>
      </div>
      <div class="wrap">
        <div class="wall wall-right"></div>
        <div class="wall wall-left"></div>
        <div class="wall wall-top"></div>
        <div class="wall wall-bottom"></div>
        <div class="wall wall-back"></div>
      </div>
      <div class="fox">
        <h1 class="centraltext2" style="font-family: Georgia, 'Times New Roman', Times, serif; color: wheat;">Fancy</h1>
      </div>
      <div class="img-container">
        <img class="fade-in-image " src="img/logo-fox.png" ></img>
      </div>
      <div class="fox">
        <h1 class="centraltext" style="font-family: Georgia, 'Times New Roman', Times, serif; color: wheat;">Fancy</h1>
      </div>
      <div class="wrap">
        <div class="wall wall-right"></div>
        <div class="wall wall-left"></div>
        <div class="wall wall-top"></div>
        <div class="wall wall-bottom"></div>
        <div class="wall wall-back"></div>
      </div>
    </div>


</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default Vue.extend({
  name: "Home",
  components: {
    HelloWorld,
  },
});
</script>

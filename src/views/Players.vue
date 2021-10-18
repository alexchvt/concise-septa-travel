<template>
  <div class="home">
    <PlayersList></PlayersList>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import PlayersList from "@/components/PlayersList.vue"; // @ is an alias to /src

@Options({
  components: {
    PlayersList,
  },
})
export default class Players extends Vue {}
</script>

<template>
  <div class="home">
    <base-component title="Alexey Bachin"></base-component>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import BaseComponent from "@/components/BaseComponent.vue"; // @ is an alias to /src

@Options({
  components: {
    BaseComponent,
  },
})
export default class Home extends Vue {}
</script>

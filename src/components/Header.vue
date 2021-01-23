<template>
  <div class="header">
    <button @click="onClickBtn">lllll
    </button>
  </div>
</template>

<script lang="ts">
import {
  Component,
  Inject,
  Model,
  Prop,
  Provide,
  Vue,
  Watch,
} from "nuxt-property-decorator"

@Component
export default class Header extends Vue {
  onClickBtn(){
    console.log("lll")
  }
}

</script>

<style>
</style>

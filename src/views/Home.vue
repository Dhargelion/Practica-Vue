<template>
  <div class="home">
    <Login />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Login from "../components/Login.vue";

@Options({
  components: {
    Login,
  },
})
export default class Home extends Vue {}
</script>

<script lang="ts">
import { Name, Description } from "../assets/Messages.json";
export default {
  data() {
    return {
      name: Name,
      description: Description,
    };
  },
};
</script>

<template>
  <h1>{{ name }}</h1>
  <h3>{{ description }}</h3>
  <div id="buttons"><button onclick="window.location.href='https://npmjs.com/package/pteromanager'">NPM</button onclick="window.location.href='/documentation'"><button>Documentation</button></div>
  <h1>Work in progress! We are still adding cool things, come back soon!</h1>
</template>

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
  <div id="buttons"><button>NPM</button><button>Documentation</button></div>
</template>

<script>
import { Description } from "../assets/Messages.json";
export default {
  data() {
    return {
      description: Description
    }
  }
}
</script>

<template>
    <h1>PteroManager</h1>
    <h3>{{description}}</h3>
    <div id="buttons">
        <button>NPM</button><button>Documentation</button>
    </div>
</template>
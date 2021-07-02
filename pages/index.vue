<template>
  <div>
    {{ info }}
  </div>
</template>

<script>
import info from "./raw.weird";

export default {
  async asyncData() {
    return { info };
  }
};
</script>

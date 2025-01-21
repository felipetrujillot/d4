<script setup lang="ts">
import { run } from "../assets/play.core/src/run.js";
import * as program from "../assets/play.core/src/programs/basics/time_milliseconds.js";

defineProps<{
  color: string;
}>();
const preEl = ref(null);
onMounted(() => {
  // Import a custom program; with at least a main() function exported

  // Run settings can override the default- and program seetings.
  // See the API for details.
  const settings = {
    fps: 60,
    element: preEl.value,
    restoreState: false,
  };

  try {
    // Boot (returns a promise)
    run(program, settings).catch(function (e) {
      console.log(e);
      console.warn(e.message);
      console.log(e.error);
    });
  } catch (error) {
    console.log(error);
  }
});
</script>

<template>
  <div class="new">
    <pre :class="color" ref="preEl"></pre>
  </div>
</template>

<style scoped>
.new {
  font-size: 1em;
  line-height: 1.2;
  font-family: "Simple Console", monospace;
}
pre {
  position: absolute;
  margin: 0;
  padding: 0;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  font-family: inherit;
}
</style>

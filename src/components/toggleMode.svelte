<script lang="ts">
    import { toggleMode } from "mode-watcher";
    import { Button } from "$lib/components/ui/button/index.js";
  </script>
   
  <Button on:click={toggleMode} variant="outline" size="icon">
    <span class="sr-only">Toggle theme</span>
  </Button>
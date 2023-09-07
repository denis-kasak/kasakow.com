<script lang="ts">
  import "../app.postcss";
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<div class="p-8 flex h-screen">
  <AppShell>
    <slot />
  </AppShell>
</div>

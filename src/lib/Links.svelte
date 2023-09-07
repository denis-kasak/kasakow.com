<script>
  import { goto } from "$app/navigation";
  import Icon from "svelte-awesome/components/Icon.svelte";
  import githubSquare from "svelte-awesome/icons/githubSquare";
  import linkedinSquare from "svelte-awesome/icons/linkedinSquare";
</script>

<div class="flex flex-row justify-center gap-2">
  <button
    on:click={() => goto("https://www.linkedin.com/in/denis-kasakow/")}
    class="btn variant-ghost-primary"
  >
    <span> <Icon data={linkedinSquare} scale={1.5} /></span>
    <span>LinkedIn</span>
  </button>
  <button
    on:click={() => goto("https://github.com/denis-kasak/")}
    class="btn variant-ghost-primary"
  >
    <span> <Icon data={githubSquare} scale={1.5} /></span>
    <span>GitHub</span>
  </button>
</div>

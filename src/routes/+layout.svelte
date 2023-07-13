<script lang="ts">
  import '../app.css'
</script>

<div class="flex items-center flex-col justify-center min-h-full flex-1 dark:text-gray-200">
  <slot></slot>
</div>

<style>
  :global(html), :global(body), :global(.app-container) {
    min-height: 100vh;
  }

  :global(.app-container) {
    display: flex;
  }
</style>

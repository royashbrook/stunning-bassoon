<script>
  import Content from './Content.svelte'
  // if there are reasons to not show the app, can set them here
  //  for me this is a placeholder for logins or fetching data
  let reasons = true;
</script>

{#if reasons}
<Content />
{/if}

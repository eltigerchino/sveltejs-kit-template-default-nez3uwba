<script>
  import { page as pageState } from '$app/state'
  import { page as pageStore } from '$app/stores'

  console.log('state', pageState.url.host, pageState.params);
  console.log('store', $pageStore.url.host, $pageStore.params);
</script>

<a href="/">Go back to home</a>

<script>
  import { page as pageState } from '$app/state'
  import { page as pageStore } from '$app/stores'

  console.log('state', pageState.url.host, pageState.params);
  console.log('store', $pageStore.url.host, $pageStore.params);
</script>

<p>state: {pageState.url.host}</p>
<p>store: {$pageStore.url.host}</p>

<a href="/">Go back to home</a>

<script lang="ts">
  import VisibilityProvider from './providers/VisibilityProvider.svelte';
  import ConvertUnix from './components/ConvertUnix.svelte';
  import { debugData } from './utils/debugData';

  debugData([
    {
      action: 'setVisible',
      data: true,
    },
  ]);
</script>

<main>
  <VisibilityProvider>
    <ConvertUnix />
  </VisibilityProvider>
</main>

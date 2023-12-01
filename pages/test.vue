<template>
  <div class="page">
    <h1>Page title</h1>

    <alert :message="'Error Error!'" :type="'error'" />
  </div>
</template>

<script>
import Alert from '@/components/header/alert';

export default {
  name: 'basic-page',
  components: { Alert }
}
</script>
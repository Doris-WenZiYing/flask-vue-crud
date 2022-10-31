<template>
  <div>
    <b-alert variant="success" show>{{ message }}</b-alert>
    <br>
  </div>
</template>

<script>
import { BAlert } from 'bootstrap-vue';

export default {
  props: ['message'],
  components: {
    BAlert,
  },
};
</script>

<template>
  <div>
    <h1>Not Authenticated</h1>
    <button class="btn btn-outline-dark"><icon name="sign-in"></icon>Cognito Hosted UI</button>
  </div>
</template>

<script lang="ts">

import 'vue-awesome/icons/sign-in';
import Icon from 'vue-awesome/components/Icon.vue';
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
    Icon,
  },
})
export default class Home extends Vue {}
</script>
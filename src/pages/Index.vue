<template>
  <q-page class="fit row">
    <app-framework appid='users' :rows-per-page="5" class="col">
    </app-framework>
  </q-page>
</template>

<script>
import AppFramework from 'src/components/framework/AppFramework.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { AppFramework },
  name: 'PageIndex',
  data: function () {
    return {}
  },

  methods: function () {

  }
})
</script>

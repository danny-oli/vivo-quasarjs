<template>
  <q-page class="q-pa-lg">
    <h4 class="q-mt-none">History</h4>

    <HistoryTable />
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import HistoryTable from '../components/HistoryTable.vue'

export default defineComponent({
  name: "HistoryPage",
  data() {
    return {
      searchHistory: null,
    };
  },

  components: {
    HistoryTable
  },
});
</script>

<style lang="scss" scoped>

</style>

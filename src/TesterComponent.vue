<template>
  <div>
    <h1>Test my component</h1>
    <hr>
    <ChipsMultiselect v-model="selectedItems" :items='items3' :sorting-property="'name'" />
    <!-- <ChipsMultiselect v-model="selectedItems" :items='items2' /> -->
  </div>
</template>

<script>
import ChipsMultiselect from "./ChipsMultiselect";
export default {
  data() {
    return {
      selectedItems: null,
      items: [
        {
          id: 1,
          name: 'Ruhul Amin'
        },
        {
          id: 2,
          name: 'Titon'
        },
        {
          id: 3,
          name: 'Sumon'
        },
        {
          id: 4,
          name: 'Suzon'
        },
        {
          id: 5,
          name: 'Fahim'
        },
        {
          id: 6,
          name: 'Pritom'
        },
        {
          id: 7,
          name: 'Peash'
        },
        {
          id: 8,
          name: 'Simanto'
        },
        {
          id: 9,
          name: 'Shuvo'
        },
        {
          id: 10,
          name: 'Yasin'
        },
        {
          id: 11,
          name: 'Shiza'
        },

      ],
      items2: ['Ruhul Amin', 'Titon', 'Sumon', 'Suzon'],
      items3: [
        {
          id: 6,
          name: 'Javascript'
        },
        {
          id: 7,
          name: 'PHP'
        },
        {
          id: 8,
          name: 'Node'
        },
        {
          id: 9,
          name: 'Python'
        },
        {
          id: 10,
          name: 'Rust'
        },
        {
          id: 11,
          name: 'Java'
        },
      ]
    }
  },
  components: {
    ChipsMultiselect
  }
}
</script>
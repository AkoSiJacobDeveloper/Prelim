<template>
  <div>
    <ItemList :items="items" />
  </div>
</template>

<script>
import ItemList from './components/ItemList.vue'

export default {
  name: 'App',
  components: {
    ItemList
  },
  data() {
    return {
      items: [
        { id: 1, name: 'Item 1', price: 10, isVisible: true },
        { id: 2, name: 'Item 2', price: 20, isVisible: true },
        { id: 3, name: 'Item 3', price: 30, isVisible: true },
        { id: 4, name: 'Item 4', price: 40, isVisible: true },
        { id: 5, name: 'Item 5', price: 50, isVisible: true },
        { id: 6, name: 'Item 6', price: 60, isVisible: true }
      ]
    }
  }
}
</script>

<style scoped></style>

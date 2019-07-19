<template>
  <div class="hello">
    <Book v-for="item in books" :key="item.id" :title="item.title"/>
  
  </div>
</template>

<script>
import Book from './Book.vue';
export default {
  name: 'Library',
  props: {
    books: Array
  },
  components: {
    Book
  }
}
</script>
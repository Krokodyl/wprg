<template>
  <div>
    <p>{{ title }}</p>
    
  </div>
</template>

<script>
export default {
  name: 'Book',
  props: {
    title: String
  }
}
</script>
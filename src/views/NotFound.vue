<template>
  <div>
    <h1>Oops!</h1>
    <h3>{{ resource }} not found.</h3>
    <router-link :to="{ name: 'event-list' }">
      Back to the home page</router-link
    >
  </div>
</template>

<script>
export default {
  props: {
    resource: {
      type: String,
      required: true
    }
  }
}
</script>
<!-- eslint-disable prettier/prettier -->
<!-- eslint-disable prettier/prettier -->
<template>
  <div>
    <h1>{{ event.title }}</h1>
    <p>{{ event.time }} on {{ event.date }} @ {{ event.location }}</p>
  </div>
</template>

<script>
export default {
  name: "EventDetails",
  data() {
    return {
      event: null,
    };
  },
  created() {
    // fetch event (by id) and set local data
  },
};
</script>

<style></style>

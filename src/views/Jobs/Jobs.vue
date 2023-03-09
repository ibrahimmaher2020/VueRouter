<template>
  <h1>Jobs Page</h1>
  <div v-for="job in jobs" :key="job">
    <h2>{{ job.titel }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      jobs: [
        { title: "It manager", id: 1, detail: "lorem" },
        { title: "Accounts Manager", id: 2, detail: "lorem" },
        { title: "Accounter", id: 3, detail: "lorem" },
      ],
    };
  },
};
</script>

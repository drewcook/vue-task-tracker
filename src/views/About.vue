<template>
  <h3>About</h3>
  <p>
    This app is built with Vue.js and uses the <em>json-server</em> NPM package
    to spin up a local server with mock data.
  </p>
  <p>
    This TODO list reads, writes, updates, and deletes from that mock server.
    The sever can be found at
    <em>localhost:5000/tasks.</em>
  </p>
  <router-link to="/">Go Back</router-link>
</template>

<style scoped>
p {
  margin-bottom: 15px;
}
em {
  background: #eee;
}
</style>

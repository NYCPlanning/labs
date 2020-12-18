<template>
  <div class="row home align-items-center">
    <div class="col-9 mx-auto">
      <h1
        class="display-4 greeting-header"
      >
        Hi! We're Labs.
      </h1>
      <h1
        class="display-4 text-white"
      >
        <strong>
          We build modern software to improve data access,
          engage communities, and empower planners in
          <span class="text-nowrap">
            New York City
          </span>
        </strong>
      </h1>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Home',
    components: {}
  }
</script>

<style>
  .home {
    height: 500px;
  }

  .greeting-header {
    color: #ecedee;
  }
</style>

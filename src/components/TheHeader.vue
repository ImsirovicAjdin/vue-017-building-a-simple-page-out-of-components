<template>
  <div class="the-header">
    <h1 class="h1 text-success">{{header}}</h1>
  </div>
</template>

<script>
export default {
  name: "TheHeader",
  data: function() {
    return {
      header: "Just another simple header"
    };
  }
};
</script>

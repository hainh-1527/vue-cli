<template>
    <div>Home</div>
</template>

<script>
  export default {
    created() {
      axios.get('users')
        .then((response) => {
          console.log(response);
        });
    }
  }
</script>

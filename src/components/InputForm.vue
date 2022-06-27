<script>
  export default {
    data() {
      return {
        count: 0
      }
    }
  }
</script>

<style scoped>
  .container {
    width: 600px;
  }
  .button {
    float: right;
  }
</style>

<template>
  <div class="container">
    <div class="field">
      <label class="label">Write a post!</label>
      <div class="control">
        <textarea class="textarea has-fixed-size" placeholder="Textarea"></textarea>
      </div>
    </div>
    <div class="field">
      <div class="control">
        <button class="button is-link">Submit</button>
      </div>
    </div>
  </div>
</template>

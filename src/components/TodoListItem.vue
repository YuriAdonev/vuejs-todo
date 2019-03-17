<template lang="pug">
  span.todo-list-item
    span.todo-list-item-label Learn Vue
    button.btn.btn-outline-danger.btn-sm
      font-awesome-icon(icon="trash")
    button.btn.btn-outline-success.btn-sm
      font-awesome-icon(icon="exclamation")
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.todo-list-item {
  font-size: 1.25rem;
  button {
    width: 35px;
    margin: 3px;
  }
  .todo-list-item-label {
    font-size: 1.25rem;
    margin-left: 1.25rem;
    line-height: 35px;
    cursor: pointer;
    user-select: none;
  }
  &.done {
    .todo-list-item-label {
      text-decoration: line-through;
    }
  }
  &.important {
    .todo-list-item-label {
      font-weight: bold;
      color: steelblue;
    }
  }
}
</style>

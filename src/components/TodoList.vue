<template lang="pug">
  ul.list-group.todo-list
    li.list-group-item
      todo-list-item.done
    li.list-group-item
      todo-list-item.important
    li.list-group-item
      todo-list-item
</template>

<script>
import TodoListItem from './TodoListItem'
export default {
  data () {
    return {}
  },
  components: {
    todoListItem: TodoListItem
  }
}
</script>

<style lang="scss" scoped>
.todo-list {
  margin-top: 10px;
  .list-group-item {
    padding: .25rem .75rem;
  }
}
</style>

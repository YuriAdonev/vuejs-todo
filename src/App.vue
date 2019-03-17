<template lang="pug">
  #app
    app-header
    .top-panel.d-flex
      search-panel
      item-status-filter
    todo-list
</template>

<script>
import AppHeader from './components/AppHeader'
import SearchPanel from './components/SearchPanel'
import TodoList from './components/TodoList'
import ItemStatusFilter from './components/ItemStatusFilter'

export default {
  name: 'App',
  data () {
    return {}
  },
  components: {
    appHeader: AppHeader,
    searchPanel: SearchPanel,
    todoList: TodoList,
    itemStatusFilter: ItemStatusFilter
  }
}
</script>

<style lang="scss" scoped>
</style>

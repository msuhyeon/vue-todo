<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoInput></TodoInput>
    <TodoList></TodoList>
    <TodoFooter></TodoFooter>
  </div>
</template>

<script>
import TodoHeader from "./components/TodoHeader"
import TodoFooter from "./components/TodoFooter"
import TodoInput from "./components/TodoInput"
import TodoList from "./components/TodoList"

export default {
  name: 'app',
  components: {
    // 컴포넌트 태그명: 컴포넌트 내용
    "TodoHeader": TodoHeader,
    "TodoFooter": TodoFooter,
    "TodoInput": TodoInput,
    "TodoList": TodoList
  }
}
</script>

<style>

</style>

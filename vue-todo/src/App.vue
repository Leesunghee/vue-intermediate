<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoInput></TodoInput>
    <TodoList></TodoList>
    <TodoFooter></TodoFooter>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from './components/TodoList.vue'
import TodoFooter from './components/TodoFooter.vue'

// var my_cmp = {
//   template: '<div>my component</div>'
// }

// new Vue({
//   el: '',
//   components: {
//     'my-cmp': my_cmp
//   }
// });

export default {
  components: {
    // 컴프넌트 태그명 : 컴포넌트 내용
    'TodoHeader' : TodoHeader, 
    'TodoInput' : TodoInput,
    'TodoList' : TodoList,
    'TodoFooter' : TodoFooter

  }
};
</script>

<style lang="scss">
</style>

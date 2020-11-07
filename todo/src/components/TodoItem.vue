<template>
    <div class="todo_item">
        <p>
          {{todo.title}}
        </p>
    </div>
</template>
<script>
    export default {
        name: "TodoItem",
        props:["todo"]
    }
</script>
<style scoped>
 .todo_item {
     color: blue
 }
</style>
<template>
    <div id="header">
        <p v-for="todo in todos" v-bind:key="todo.id"></p>
        <p>{{todo}}</p>
       <p>{{due}}</p>

        <h1>test</h1>
    </div>
</template>

<script>
    export default {
        name: "header",
       data: todo( [{
            todo: "value",
            due:"fri"
           },
           {
               todo:"james",
               due: "mon",
           }],)
          
    }  
        
</script>

<style lang="scss" scoped>
header{
  background-color: rgba(0, 140, 255, 0.678);
  height: 100px;
  width: 100%;
  color: white;
}

</style>
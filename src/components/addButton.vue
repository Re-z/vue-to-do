<template>
    <div class="add-btn-wrap">
        <button class="add-btn" @click="bla()">Add a task</button>
    </div>

</template>
<script>
    export default {
      methods:{
        bla: function () {
          alert(1)
        }
      }
    }
</script>
<style>
    .add-btn-wrap {
        margin: 30px auto;
        text-align: center;
    }
    .add-btn {
        padding: 20px 40px;
        color: white;
        background: cornflowerblue;
        font-weight: bold;
        text-align: center;
        border-radius: 5px;
        outline: none;
        font-size: 20px;
    }
</style>

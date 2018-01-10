<template>
    <div class="todos">
        <div class="todos__item">
            Some new todo mark
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
    .todos {
      display: flex;
      flex-wrap: wrap;
      &__item{
        border: 1px solid lightgray;
        padding: 30px 10px;
        min-width: 200px;
        min-height: 100px;
        border-radius: 5px;
        font-style: italic;
        font-weight: bold;
        font-size: 20px;
        cursor: pointer;

      }
    }

</style>

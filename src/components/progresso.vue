<template>
<div class="progress">
			<input type="text" placeholder="Type your todo" class="progress__bg" :value="{newTodo}">
			<p>Items: <span class="progress__count">{{todoCounter}}</span></p>
		</div>
</template>

<script>
export default {
  data: function () {
    return {
      newTodo: 'some',
      todoCounter: 1
    }
  }
}
</script>

<style scoped>
  .progress {
    text-align: center;
  }
	.progress input {
		width: 700px;
		margin: 0 auto;
		height: 30px;
		line-height: 30px;
		color: #000;
		text-align: center;
		position: relative;
		border: 1px solid lightgray;
	}
</style>

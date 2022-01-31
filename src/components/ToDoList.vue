<template>
    <section class="todoapp">
		<header class="header">
			<h1>Super2Do</h1>
			<input class="new-todo" placeholder="What needs to be done?" autofocus>
		</header>
			
			<section class="main">
				<input id="toggle-all" class="toggle-all" type="checkbox">
				<label for="toggle-all">Mark all as complete</label>
				<ul class="todo-list">
					
					<li class="completed">
						<div class="view">
							<input class="toggle" type="checkbox" checked>
							<label>Taste JavaScript</label>
							<button class="destroy"></button>
						</div>
						<input class="edit" value="Create a Todo template">
					</li>
					<li>
						<div class="view">
							<input class="toggle" type="checkbox">
							<label>Buy a unicorn</label>
							<button class="destroy"></button>
						</div>
						<input class="edit" value="Rule the web">
					</li>
				</ul>
			</section>
			
			<footer class="footer">
				<span class="todo-count"><strong>0</strong> item left</span>
				<ul class="filters">
					<li>
						<a class="selected" href="#/">All</a>
					</li>
					<li>
						<a href="#/active">Active</a>
					</li>
					<li>
						<a href="#/completed">Completed</a>
					</li>
				</ul>
				<button class="clear-completed">Clear completed</button>
			</footer>
		</section>
</template>

<script>
// import '../assets/js/app.js';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import '../assets/css/app.css';
@import '../assets/css/base.css';
@import '../assets/css/index.css';


/* h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
} */



</style>

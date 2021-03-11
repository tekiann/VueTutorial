<template>
	<div id="app">
		<section class="hero is-primary is-bold is-fullheight">
			<div class="hero-head">
				<nav class="navbar">
					<div class="container">
						<div class="navbar-brand">
							<a href="" class="navbar-item"> VueJs Tutorial 1.0 </a>
						</div>
					</div>
				</nav>
			</div>
			<div class="hero-body">
				<div class="container">
					<div class="conteiner has-text-centered">
						<div class="row">
							<div class="columns">
								<div class="column is-half is-offset-one-quarter">
									<todo-card></todo-card>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="hero-foot">
				<div class="container">
					<div class="content has-text-centered">
						<p>
							<strong>VueJS Tutorial</strong> by
							<a href="http://github.com/kessiacastro">Késsia Castro</a>.
						</p>
					</div>
				</div>
			</div>
		</section>
	</div>
</template>

<script>
import TodoCard from "./components/TodoCard";

export default {
	name: "app",
	components: {
		TodoCard
	},
	data() {
		return {
			msg: "Hello, World!",
		};
	},
};
</script>

<style>
</style>

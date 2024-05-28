<nav class="navbar navbar-expand-lg navbar-light bg-light">
	<div class="container-fluid">
		<div class="collapse navbar-collapse" id="navbarNavDropdown">
			<h4>Sveltekit</h4>
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link active" href="/">Personas</a>
				</li>
				<li class="nav-item">
					<a class="nav-link active" href="/opcion1">Opcion 1</a>
				</li>
				<li class="nav-item">
					<a class="nav-link active" href="/opcion2">Opción 2</a>
				</li>
			</ul>
		</div>
	</div>
</nav>

<footer class="footer"><p class="ms-5 align-bottom">Esto es el pie</p></footer>
<slot />

<style>
	.footer {
		position: absolute;
		bottom: 0;
		width: 100%;
		height: 40px;
		background-color: #f5f5f5;
	}
</style>

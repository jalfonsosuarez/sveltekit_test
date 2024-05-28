<div class="container">
	<div class="row align-items-start">
		<div class="col">
			<h1>Personas</h1>
		</div>
		<div class="col d-md-flex justify-content-md-end">
			<button
				type="button"
				class="btn btn-sm btn-primary"
				data-bs-toggle="modal"
				data-bs-target="#staticBackdrop"
			>
				<i class="bi bi-file-earmark-plus pe-1"></i>
				Añadir
			</button>
		</div>
		<!-- Button trigger modal -->
		<hr />
	</div>
	<table class="table table-sm table-hover">
		<thead>
			<tr>
				<th scope="col">#</th>
				<th scope="col">First</th>
				<th scope="col">Last</th>
				<th scope="col">Handle</th>
				<th scope="col"></th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<th scope="row">1</th>
				<td>Mark</td>
				<td>Otto</td>
				<td>@mdo</td>
				<td align="right">
					<button type="button" class="btn btn-sm btn-success"
						><i class="bi bi-pencil-square"></i></button
					>
					<button type="button" class="btn btn-sm btn-danger"><i class="bi bi-file-x"></i></button>
				</td>
			</tr>
			<tr>
				<th scope="row">2</th>
				<td>Jacob</td>
				<td>Thornton</td>
				<td>@fat</td>
				<td align="right">
					<button type="button" class="btn btn-sm btn-success"
						><i class="bi bi-pencil-square"></i></button
					>
					<button type="button" class="btn btn-sm btn-danger"><i class="bi bi-file-x"></i></button>
				</td>
			</tr>
			<tr>
				<th scope="row">3</th>
				<td colspan="2">Larry the Bird</td>
				<td>@twitter</td>
				<td align="right">
					<button type="button" class="btn btn-sm btn-success"
						><i class="bi bi-pencil-square"></i></button
					>
					<button type="button" class="btn btn-sm btn-danger"><i class="bi bi-file-x"></i></button>
				</td>
			</tr>
		</tbody>
	</table>
</div>

<!-- Modal -->
<div
	class="modal fade"
	id="staticBackdrop"
	data-bs-backdrop="static"
	data-bs-keyboard="false"
	tabindex="-1"
	aria-labelledby="staticBackdropLabel"
	aria-hidden="true"
>
	<div class="modal-dialog">
		<div class="modal-content">
			<div class="modal-header">
				<h1 class="modal-title fs-5" id="staticBackdropLabel">Modal title</h1>
				<button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
			</div>
			<div class="modal-body">
				<form>
					<div class="mb-3">
						<label for="exampleInputEmail1" class="form-label">Email address</label>
						<input
							type="email"
							class="form-control"
							id="exampleInputEmail1"
							aria-describedby="emailHelp"
						/>
						<div id="emailHelp" class="form-text">
							We'll never share your email with anyone else.
						</div>
					</div>
					<div class="mb-3">
						<label for="exampleInputPassword1" class="form-label">Password</label>
						<input type="password" class="form-control" id="exampleInputPassword1" />
					</div>
					<div class="mb-3 form-check">
						<input type="checkbox" class="form-check-input" id="exampleCheck1" />
						<label class="form-check-label" for="exampleCheck1">Check me out</label>
					</div>
					<div class="modal-footer">
						<button type="button" class="btn btn-secondary" data-bs-dismiss="modal"
							><i class="bi bi-box-arrow-left pe-1"></i>Salir</button
						>
						<button type="submit" class="btn btn-primary" data-bs-dismiss="modal"
							><i class="bi bi-save pe-1"></i>Guardar</button
						>
					</div>
				</form>
			</div>
		</div>
	</div>
</div>

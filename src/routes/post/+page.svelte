<script>

</script>

<main class="Large">
	<!-- Naigation Section -->
	<section class="Navigation-Section container-fluid fixed-top">
		<div class="row Naivgation-Container">
			<div class="col-lg-6 col-md-6 Navigation-Left-Container">
				<h4 class="Navigation-Tilte">
					<svg
										xmlns="http://www.w3.org/2000/svg"
										width="35"
										height="35"
										fill="currentColor"
										class="bi bi-plus-circle"
										viewBox="0 0 16 16"
									>
										<path
											d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
										/>
										<path
											d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"
										/>
									</svg> Add Snippet
				</h4>
				
			</div>
			<div class="col-lg-6 col-md-6 Navigation-Right-Container">
				<a href="/notifications" class="Navigation-Notification-Container">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						width="30"
						height="30"
						fill="currentColor"
						class="bi bi-bell"
						viewBox="0 0 16 16"
					>
						<path
							d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z"
						/>
					</svg>
				</a>
				<div class="Navigation-Profile-Container">
					<p class="Navigation-Profile-Username">Dosu_E</p>
					<img src="/images/home/profile.jpg" alt="" />
				</div>
				<div
					class="Navigation-Menu-Toggler"
					type="button"
					data-bs-toggle="offcanvas"
					data-bs-target="#offcanvasDarkNavbar"
					aria-controls="offcanvasDarkNavbar"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						width="30"
						height="30"
						fill="currentColor"
						class="bi bi-list"
						viewBox="0 0 16 16"
					>
						<path
							fill-rule="evenodd"
							d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"
						/>
					</svg>
				</div>
				<div
					class="offcanvas offcanvas-end Navigation-Menu"
					tabindex="-1"
					id="offcanvasDarkNavbar"
					aria-labelledby="offcanvasDarkNavbarLabel"
				>
					<div class="offcanvas-header">
						<h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">
							<img src="/images/index/sb.png" width="80rem" alt="" />
						</h5>
						<button
							type="button"
							class="btn-close btn-close-white"
							data-bs-dismiss="offcanvas"
							aria-label="Close"
						/>
					</div>
					<div class="offcanvas-body">
						<ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
							<li class="nav-item ">
								<a class="nav-link" aria-current="page" href="/home"
									><svg
										xmlns="http://www.w3.org/2000/svg"
										width="40"
										height="40"
										fill="currentColor"
										class="bi bi-house-door-fill"
										viewBox="0 0 16 16"
									>
										<path
											d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5Z"
										/>
									</svg> Home</a
								>
							</li>
							<li class="nav-item">
								<a class="nav-link" href="/discover"
									><svg
										xmlns="http://www.w3.org/2000/svg"
										width="40"
										height="40"
										fill="currentColor"
										class="bi bi-search"
										viewBox="0 0 16 16"
									>
										<path
											d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
										/>
									</svg> Discover</a
								>
							</li>
							<li class="nav-item Active-Link">
								<a class="nav-link" aria-current="page" href="/post"
									><svg
										xmlns="http://www.w3.org/2000/svg"
										width="40"
										height="40"
										fill="currentColor"
										class="bi bi-plus-circle"
										viewBox="0 0 16 16"
									>
										<path
											d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
										/>
										<path
											d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"
										/>
									</svg> Add Snippet</a
								>
							</li>
							<li class="nav-item">
								<a class="nav-link" href="/profile"
									><svg
										xmlns="http://www.w3.org/2000/svg"
										width="40"
										height="40"
										fill="currentColor"
										class="bi bi-person"
										viewBox="0 0 16 16"
									>
										<path
											d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"
										/>
									</svg> Profile</a
								>
							</li>
						</ul>
						<hr />

						
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Add Section -->
	<section class="Add-Section container-fluid">
		<div class="row Add-Container">
			<form>
				<div class="mb-3">
					<textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Type in your code here" rows="15"></textarea>
				  </div>
				  <div class="mb-3">
					<label for="exampleFormControlText" class="form-label">Add a title for your snippet</label>

					<input class="form-control" type="text" aria-label="default input example">
				</div>
				<div class="mb-3">
					<label for="exampleFormControlTextarea1" class="form-label">Description</label>
					<textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
				</div>
				<div class="mb-3">
					<label for="exampleFormControlText" class="form-label">Add tags for your snippet</label>

					<input class="form-control" type="text" aria-label="default input example">
				</div>
				<p>Separate each tag with a coma.</p>
				<button type="submit" class="btn btn-light">Post Snippet</button><br>
				<button type="submit" class="btn btn-outline-light">Save As A Draft</button>

			</form>
		</div>
	</section>
</main>

<!-- small screen -->
<main class="Small">
	<strong>Switch to Desktop, Laptop or Tablet. <br><br><br> Mobile Phone version not AVAILABLE</strong>
</main>

<style>
	/* Target Desktops and Laptops */
	@media screen and (min-width: 992px) {
		/* Main */
		p {
			font-size: 1.2rem;
		}

		/* Navigation */
		.Navigation-Section {
			padding: 1rem 3rem;
			background-color: #121b2c;
		}
		.Naivgation-Container h4 {
			display: inline-block;
		}

		.Navigation-Right-Container {
			text-align: right;
		}
		.Navigation-Notification-Container {
			display: inline-block;
			margin-right: 2rem;
			padding: 0.8rem;
			border-radius: 100%;
			background-color: #1d2a44;
		}
		a.Navigation-Notification-Container{
			color: white;
		}

		.Navigation-Profile-Container {
			display: inline-block;
			height: 100%;
		}
		.Navigation-Profile-Container img {
			height: 100%;
			border-radius: 100%;
		}
		.Navigation-Profile-Username {
			display: inline-block;
			margin-right: 1rem;
		}
		.Navigation-Menu-Toggler {
			display: inline-block;
			margin-left: 2rem;
			padding: 0.8rem;
			border-radius: 0.5rem;
			background-color: #1d2a44;
		}
		.offcanvas {
			background-color: #0c121d;
			color: grey;
			text-align: left;
			font-size: 1.5rem;
		}
		.nav-item {
			margin-bottom: 3rem;
		}
		.nav-item:hover {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding-left: 2rem;
			color: white;
		}
		.nav-item svg {
			margin-right: 1rem;
		}
		.nav-item.Active-Link {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding-left: 2rem;
			color: white;
		}

		/* Add */
		.Add-Container {
			padding: 10rem 5rem 3rem;
		}
		

		main.Small {
			display: none;
		}
	}

	/* Target Tablets */
	@media screen and (min-width: 700px) and (max-width: 991px) {
		/* Main */
		p {
			font-size: 1.2rem;
		}

		/* Navigation */
		.Navigation-Section {
			padding: 1rem 1rem;
			background-color: #121b2c;
		}
		.Naivgation-Container h4 {
			display: inline-block;
		}

		

		.Navigation-Right-Container {
			text-align: right;
		}
		.Navigation-Notification-Container {
			display: inline-block;
			margin-right: 2rem;
			padding: 0.8rem;
			border-radius: 100%;
			background-color: #1d2a44;
		}
		a.Navigation-Notification-Container{
			color: white;
		}
		.Navigation-Profile-Container {
			display: inline-block;
			height: 100%;
		}
		.Navigation-Profile-Container img {
			height: 4rem;
			border-radius: 100%;
		}
		.Navigation-Profile-Username {
			display: inline-block;
			margin-right: 1rem;
		}
		.Navigation-Menu-Toggler {
			display: inline-block;
			margin-left: 2rem;
			padding: 0.8rem;
			border-radius: 0.5rem;
			background-color: #1d2a44;
		}
		.offcanvas {
			background-color: #0c121d;
			color: grey;
			text-align: left;
			font-size: 1.5rem;
		}
		.nav-item {
			margin-bottom: 3rem;
		}
		.nav-item:hover {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding-left: 2rem;
			color: white;
		}
		.nav-item svg {
			margin-right: 1rem;
		}
		.nav-item.Active-Link {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding-left: 2rem;
			color: white;
		}

		/* Add */
		.Add-Container {
			padding: 10rem 5rem 3rem;
		}
		
		main.Small {
			display: none;
		}
	}

	/* Phone screens */
	@media screen and (max-width: 699px) {
		main.Large {
			display: none;
		}
		main.Small{
			display: grid;
			place-items: center;
			height: 100vh;
			padding: 1.5rem;
			font-size: 2rem;
		}
	}

	/* General */
	.Navigation-Section {
		border-bottom: solid 2px #434343;
	}
	textarea, input{
		background-color: #1D2A44;
		border-color: #1D2A44;
		color: white;
		border-radius: 2rem;
	}
	.Add-Section p{
		text-align: right;
	}
	button{
		border-radius: 2rem;
		width: 100%;
		margin-bottom: 2rem;
		padding-top: 0.5rem;
		padding-bottom: 0.5rem;
		font-size: 1.5rem;

	}
	::placeholder {
  color: white;
  font-size: 1rem;
}
</style>

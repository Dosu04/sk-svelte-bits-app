<script>
	// Like Button
	let count = 1;
	let liked = false;

	function like() {
		if (!liked) {
			count--;

			liked = true;
		} else {
			count++;

			liked = false;
		}
	}
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
						class="bi bi-house-door-fill"
						viewBox="0 0 16 16"
					>
						<path
							d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5Z"
						/>
					</svg> Home
				</h4>
				<div class="Navigation-Switch-Container">
					<a href="/home" class="btn btn-light Navigation-Switch-Button">Explore Feed</a>
					<a href="/home/collection" class="btn btn-light Navigation-Switch-Button Active-Button"
						>Collection</a
					>
				</div>
			</div>
			<div class="col-lg-6 col-md-6 Navigation-Right-Container">
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
							<li class="nav-item Active-Link">
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
							<li class="nav-item">
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

	<!-- Feed Section -->
	<section class="Feed-Section container-fluid">
		<div class="row Feed-Container">
			<div class="col-lg-12 Feed-Snippet-Container">
				<a href="/otherprofile" class="row Feed-Snippet-Heading-Container">
					<img src="/images/home/other.jpg" alt="" />
					<p class="Feed-Snippet-Text-Container">
						Philip_Kobz<br /><span
							><svg
								xmlns="http://www.w3.org/2000/svg"
								width="16"
								height="16"
								fill="currentColor"
								class="bi bi-clock-history"
								viewBox="0 0 16 16"
							>
								<path
									d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"
								/>
								<path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z" />
								<path
									d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"
								/>
							</svg> Just Now</span
						>
					</p>
				</a>
				<div class="row Feed-Snippet-Details-Container">
					<h3 class="Feed-Snippet-Title">Worked on this yesterday, blah blah blah</h3>
					<img src="/images/home/snippets.png" class="Feed-Snippet" alt="" />
				</div>

				<div class="row Feed-Snippet-Interactions Large">
					<div class="col-sm-4 Feed-Snippet-Like">
						<button class="Like-Button" on:click={like}>
							{#if liked}
								<svg
									xmlns="http://www.w3.org/2000/svg"
									width="50"
									height="50"
									fill="white"
									class="bi bi-heart-fill"
									viewBox="0 0 16 16"
								>
									<path
										fill-rule="evenodd"
										d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"
									/>
								</svg>
							{:else}
								<svg
									xmlns="http://www.w3.org/2000/svg"
									width="50"
									height="50"
									fill="red"
									class="bi bi-heart-fill"
									viewBox="0 0 16 16"
								>
									<path
										fill-rule="evenodd"
										d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"
									/>
								</svg>
							{/if}

							<span class="Like-Counter"> {count}</span>
						</button>
					</div>

					<div class="col-sm-4">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="50"
							height="50"
							fill="currentColor"
							class="bi bi-share-fill"
							viewBox="0 0 16 16"
						>
							<path
								d="M11 2.5a2.5 2.5 0 1 1 .603 1.628l-6.718 3.12a2.499 2.499 0 0 1 0 1.504l6.718 3.12a2.5 2.5 0 1 1-.488.876l-6.718-3.12a2.5 2.5 0 1 1 0-3.256l6.718-3.12A2.5 2.5 0 0 1 11 2.5z"
							/>
						</svg>
					</div>
				</div>
			</div>
		</div>
	</section>
</main>

<!-- small screen -->
<main class="Small">
	<strong
		>Switch to Desktop, Laptop or Tablet. <br /><br /><br /> Mobile Phone version not AVAILABLE</strong
	>
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

		.Navigation-Switch-Container {
			display: inline-block;
			margin-left: 2rem;
			padding: 1rem 1rem;
			background-color: #0c121d;
			border-radius: 2rem;
		}
		.Navigation-Switch-Button {
			background-color: #0c121d;
			border-color: #0c121d;
			color: white;
			border-radius: 2rem;
			margin: 0 0.2rem;
			padding-left: 1rem;
			padding-right: 1rem;
		}
		.Navigation-Switch-Button.Active-Button {
			background-color: #1d2a44;
			color: white;
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
		a.Navigation-Notification-Container {
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

		/* Feed */
		.Feed-Container {
			padding: 15rem 12rem 3rem;
		}
		.Feed-Snippet-Container {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding: 3rem;
			margin-bottom: 4rem;
		}
		.Feed-Snippet-Heading-Container img {
			width: 7rem;
			display: inline;
			border-radius: 100%;
			margin-bottom: 2rem;
		}
		.Feed-Snippet-Text-Container {
			display: inline;
			width: 8rem;
		}
		.Feed-Snippet-Text-Container span {
			color: grey;
			font-size: 15px;
		}
		.Feed-Snippet-Title {
			margin-bottom: 1rem;
		}
		.Feed-Snippet {
			border-radius: 5rem;
		}
		.Feed-Snippet-Interactions {
			margin-top: 3rem;
			margin-bottom: 3rem;
			text-align: center;
		}
		.Like-Button svg {
			margin-right: 5px;
			vertical-align: middle;
		}

		.Like-Counter {
			color: white;
			font-size: 2rem;
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

		.Navigation-Switch-Container {
			display: inline-block;
			margin-left: 2rem;
			padding: 0.5rem 0.5rem;
			background-color: #0c121d;
			border-radius: 2rem;
		}
		.Navigation-Switch-Button {
			background-color: #0c121d;
			border-color: #0c121d;
			color: white;
			border-radius: 2rem;
			margin: 0 0.2rem;
			padding-left: 1rem;
			padding-right: 1rem;
		}
		.Navigation-Switch-Button.Active-Button {
			background-color: #1d2a44;
			color: white;
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

		/* Feed */
		.Feed-Container {
			padding: 15rem 5rem 3rem;
		}
		.Feed-Snippet-Container {
			background-color: #1d2a44;
			border-radius: 2rem;
			padding: 3rem;
			margin-bottom: 4rem;
		}
		.Feed-Snippet-Heading-Container img {
			width: 7rem;
			display: inline;
			border-radius: 100%;
			margin-bottom: 2rem;
		}
		.Feed-Snippet-Text-Container {
			display: inline;
			width: 8rem;
		}
		.Feed-Snippet-Text-Container span {
			color: grey;
			font-size: 15px;
		}
		.Feed-Snippet-Title {
			margin-bottom: 1rem;
		}
		.Feed-Snippet {
			border-radius: 5rem;
		}
		.Feed-Snippet-Interactions {
			margin-top: 3rem;
			margin-bottom: 3rem;
			text-align: center;
		}

		.Like-Button svg {
			margin-right: 5px;
			vertical-align: middle;
		}

		.Like-Counter {
			color: white;
			font-size: 2rem;
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
		main.Small {
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
	.Like-Button {
		background-color: transparent;
		border: none;
		cursor: pointer;
		display: flex;
		align-items: center;
	}

	
	a{
		text-decoration: none;
		color: white;
	}
</style>

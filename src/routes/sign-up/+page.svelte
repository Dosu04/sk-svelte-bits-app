<script>
</script>

<main class="container-fluid">
	<div class="row">
		<div class="Onboarding-Carousel-Container col-lg-7 col-md-12">
			<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
				<div class="carousel-indicators">
					<button
						type="button"
						data-bs-target="#carouselExampleCaptions"
						data-bs-slide-to="0"
						class="active"
						aria-current="true"
						aria-label="Slide 1"
					/>
					<button
						type="button"
						data-bs-target="#carouselExampleCaptions"
						data-bs-slide-to="1"
						aria-label="Slide 2"
					/>
					<button
						type="button"
						data-bs-target="#carouselExampleCaptions"
						data-bs-slide-to="2"
						aria-label="Slide 3"
					/>
				</div>
				<div class="carousel-inner">
					<div class="carousel-item active">
						<img src="/images/index/onboard (1).png" class="d-block w-100" alt="..." />
						<div class="overlay" />
						<div class="carousel-caption d-none d-md-block">
							<h2>Easy Sharing</h2>
							<p>
								Quickly and easily share your Svelte code snippets with others. Our sharing tools
								allow you to share either individual snippets or entire collections.
							</p>
						</div>
					</div>
					<div class="carousel-item">
						<img src="/images/index/onboard (3).png" class="d-block w-100" alt="..." />
						<div class="overlay" />
						<div class="carousel-caption d-none d-md-block">
							<h2>Personal Collection</h2>
							<p>
								Save your favorite Svelte code snippets to your own personal collection. Easily
								access and reference your favorite code whenever you need it.
							</p>
						</div>
					</div>
					<div class="carousel-item">
						<img src="/images/index/onboard (2).png" class="d-block w-100" alt="..." />
						<div class="overlay" />

						<div class="carousel-caption d-none d-md-block">
							<h2>Search and Discover</h2>
							<p>
								Browse by category or use our advanced search filters to find exactly what you’re
								looking for.
							</p>
						</div>
					</div>
				</div>
				<button
					class="carousel-control-prev"
					type="button"
					data-bs-target="#carouselExampleCaptions"
					data-bs-slide="prev"
				>
					<span class="carousel-control-prev-icon" aria-hidden="true" />
					<span class="visually-hidden">Previous</span>
				</button>
				<button
					class="carousel-control-next"
					type="button"
					data-bs-target="#carouselExampleCaptions"
					data-bs-slide="next"
				>
					<span class="carousel-control-next-icon" aria-hidden="true" />
					<span class="visually-hidden">Next</span>
				</button>
			</div>
		</div>

		<div class="Onboarding-Form-Container col-lg-5 col-md-12">
			<form>
                <div class="Onboarding-Header">
                    <div class="Onboarding-Image-Container">
                        <img src="/images/index/sb.png" class="Onboarding-Image" width="50rem" alt="">
                    </div>
                    <div class="Oboarding-Title-Container">
                        <h3 class="Onboarding-Title">Welcome to Svelte Bits!</h3>
                    </div>
                </div>
                <div class="mb-3">
					<label for="exampleInputEmail1" class="form-label">Enter your Full Name (Surname First)</label>
					<input
						type="text"
						class="form-control"
						id="exampleInputName1"
						aria-describedby="nameHelp"
					/>
				</div>
                <div class="mb-3">
					<label for="exampleInputEmail1" class="form-label">Enter your Username</label>
					<input
						type="text"
						class="form-control"
						id="exampleInputName1"
						aria-describedby="nameHelp"
					/>
				</div>
				<div class="mb-3">
					<label for="exampleInputEmail1" class="form-label">Enter your Email Address</label>
					<input
						type="email"
						class="form-control"
						id="exampleInputEmail1"
						aria-describedby="emailHelp"
					/>
				</div>
				<div class="mb-3">
					<label for="exampleInputPassword1" class="form-label">Enter your Password</label>
					<input type="password" class="form-control" id="exampleInputPassword1" />
				</div>

				<a href="/home" type="submit" style="" class="btn btn-success Onboarding-Submit-Button">Sign Up</a> 
                
                <hr>
                <div class="Onboarding-Button-Container">
                    <a href="" class="btn btn-outline-light Onboarding-Button Google"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-google" viewBox="0 0 16 16">
                        <path d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z"/>
                      </svg> Sign up with Google</a> 
                    <a href=""class="btn btn-outline-light Onboarding-Button "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                        <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                      </svg> Sign up with Github</a>

                </div>
                <div class="Onboarding-Switch">
                    <p>Already have an account? <a href="/sign-in"> Log in</a></p>
                </div>
                

			</form>
		</div>
	</div>
</main>

<style>
	/* Target Desktops and Laptops */
	@media screen and (min-width: 992px) {
		.row {
			height: 100vh;
		}
		.Onboarding-Carousel-Container {
			display: grid;
			place-items: center;
			padding: 5rem;
		}
		
		.carousel-item {
			position: relative;
		}
		.carousel-item img {
			border-radius: 3rem;

		}

		.overlay {
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-color: rgba(0, 0, 0, 0.7);
			border-radius: 3rem;
		}


        .Onboarding-Form-Container {
			padding: 2rem 5rem;
            padding-left:0rem ;
			text-align: right;
		}
        .Onboarding-Image{
            margin-bottom: 1.3rem;
        }
        .Onboarding-Title{
            margin-bottom: 1.5rem;
        }
		input {
			background-color: #111927;
			color: #fff;
            border-radius: 2rem;
		}
		label {
			color: #b2b2b2;
		}
        .Onboarding-Submit-Button{
            width:100%;
            border-radius: 2rem;

        }
        .Onboarding-Button{
            border-radius: 2rem;

        }
        .Onboarding-Button.Google{
            margin-right: 2rem;
        }
        .Onboarding-Switch{
            margin-top: 2rem;

        }

        .Onboarding-Switch a{
            color: #1ABC00;
            text-decoration: none;
        }

	}

	/* Target Tablets */
	@media screen and (min-width: 700px) and (max-width: 991px) {
		
        .Onboarding-Carousel-Container {
			display: grid;
			place-items: center;
			padding: 5rem;
		}
		
		.carousel-item {
			position: relative;
		}
		.carousel-item img {
			border-radius: 3rem;

		}

		.overlay {
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-color: rgba(0, 0, 0, 0.7);
			border-radius: 3rem;
		}


        .Onboarding-Form-Container {
			padding: 5rem;
			text-align: right;
		}
        .Onboarding-Image{
            margin-bottom: 1.3rem;
        }
        .Onboarding-Title{
            margin-bottom: 1.5rem;
        }
		input {
			background-color: #111927;
			color: #fff;
            border-radius: 2rem;
		}
		label {
			color: #b2b2b2;
		}
        .Onboarding-Submit-Button{
            width:100%;
            border-radius: 2rem;

        }
        .Onboarding-Button{
            border-radius: 2rem;

        }
        .Onboarding-Button.Google{
            margin-right: 2rem;
        }
        .Onboarding-Switch{
            margin-top: 2rem;

        }

        .Onboarding-Switch a{
            color: #1ABC00;
            text-decoration: none;
        }

	}

	/* Phone screens */
	@media screen and (max-width: 699px) {
	
        .Onboarding-Carousel-Container {
			display: none;
			
		}
		

        .Onboarding-Form-Container {
			padding: 1rem;
			text-align: right;
		}
        .Onboarding-Image{
            margin-bottom: 1.3rem;
        }
        .Onboarding-Title{
            margin-bottom: 2.5rem;
        }
		input {
			background-color: #111927;
			color: #fff;
            border-radius: 2rem;
		}
		label {
			color: #b2b2b2;
		}
        .Onboarding-Submit-Button{
            width:100%;
            border-radius: 2rem;

        }
        .Onboarding-Button{
            border-radius: 2rem;
            width: 100%;
            margin-bottom: 1rem;

        }
        .Onboarding-Switch{
            margin-top: 2rem;

        }
        .Onboarding-Switch p{
            font-size: 0.8rem;
        } 
        .Onboarding-Switch a{
            color: #1ABC00;
            text-decoration: none;
        }    
    }

	/* General */
</style>

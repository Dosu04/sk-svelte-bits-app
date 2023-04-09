<script>
</script>

<main class="container-fluid">
    <!-- Navigation-Section -->
    <section class="Navigation-Section container-fluid"> 
        <div class="row Naivgation-Container ">
            <div class="col Navigation-Logo-Container">
                <img src="/images/sb.png" class="Navigation-Logo" alt="Svelte Bits">
            </div>
            <div class="col Navigation-Buttons-Container ">
                <a href="" type="button" class="btn btn-outline-light Navigation-Buttons" id="Log">Log In</a>
                <a href="" type="button" class="btn btn-light Navigation-Buttons" id="Reg">Get Started</a>

            </div>
        </div>

    </section>

    <!-- Hero Section -->
    <section class="Hero-Section container-fluid">
        <div class="row Hero-Container">
            <div class="col-lg-12 Hero-Text-Container">
                <h1><span>Share your own snippets</span>, discover new ones, and vote on your favorites.</h1> <br>
                <a href="" class="btn btn-light Hero-Buttons">Share my own snippet!</a>
            </div>
            <div class="col-lg-12 Hero-Image-Container">
                <img src="/images/hero.png" class="Hero-Image" alt="">
            </div>
        </div>
    </section>
    
    <!-- Features Section -->
    <section class="Features-Section container-fluid">
        <div class="row Features-Container">
            <h2>What does <span>Svelte Bits</span> have for you?</h2>
            
            <div class="col-lg-12 Line-1-Container">
                <div class="Line-1">
                    <hr>
                </div>
            </div>
            <div class="col-lg-12 Line-2-Container">
                <div class="Line-2">
                    <hr>
                </div>
            </div>
            <p>Our app features a sleek, modern design that's easy on the eyes. With a focus on simple, intuitive navigation, 
                SvelteBits allows you to quickly discover and share Svelte code snippets, all while enjoying the view.</p>
            
            <div class="Features-List">
                <p class="Features">
                    Create simple, elegant code snippets with ease.
                </p>
                <p class="Features">
                    Our app features a modern, minimalist interface.
                </p>
                <p class="Features">
                    Responsive design ensures SvelteBits looks good on any device.
                </p>
            </div>

        </div>
    </section>

    <!-- Collections Section -->
    <section class="Collections-Section container-fluid">
        <div class="container Collections-Container">
            <h2>Personal Collection</h2>
            <p>Our app features a sleek, modern design that's easy on the eyes. With a focus on simple, intuitive navigation, SvelteBits allows you to quickly discover and share Svelte code snippets, all while enjoying the view.</p>

            
            <div class="row Collections-Boxes-Container">
                <div class="col Collections-Box">
                    <h3>Organization</h3>
                    <p>Keep your favorite snippets sorted and easy to find.</p>
            
                </div>
                <div class="col Collections-Box">
                    <h3>Custom Folders</h3>
                    <p>Create custom folders to better organize your snippets.</p>
            
                </div>
                <div class="col Collections-Box">
                    <h3>Quick Access</h3>
                    <p>Quickly access your favorites with just a few clicks.</p>
            
                </div>
            </div>

        </div>
    </section>

    <!-- Discover Section -->
    <section class="Discover-Section container-fluid">
        <div class="container Discover-Container">
            <h2>Personal Collection</h2>
            <p>Our app features a sleek, modern design that's easy on the eyes. With a focus on simple, intuitive navigation, SvelteBits allows you to quickly discover and share Svelte code snippets, all while enjoying the view.</p>

            
            <div class="row Discover-Boxes-Container">
                <div class="col Discover-Box">
                    <h3>Organization</h3>
                    <p>Keep your favorite snippets sorted and easy to find.</p>
            
                </div>
                <div class="col Discover-Box">
                    <h3>Custom Folders</h3>
                    <p>Create custom folders to better organize your snippets.</p>
            
                </div>
                <div class="col Discover-Box">
                    <h3>Quick Access</h3>
                    <p>Quickly access your favorites with just a few clicks.</p>
            
                </div>
            </div>

        </div>
    </section>

    <!-- Sharing Section -->
    <section class="Sharing-Section container-fluid">
        <div class="container Sharing-Container">
            <h2>Easy Sharing</h2>
            <p>Quickly and easily share your Svelte code snippets with others. Our sharing tools allow you to share either individual snippets or entire collections.</p>

            
    </section>
</main>

<style>
    /* Target Desktops and Laptops */
    @media screen and (min-width: 992px){
        /* Main */
        p {
            font-size: 1.2rem;
        }



        /* Navigation */
        .Navigation-Section{
            padding: 1rem 8rem;
        }

        .Navigation-Logo{
            width: 4rem;
        }

        .Navigation-Buttons{
            padding-left: 2rem;
            padding-right: 2rem;
        }

        .Navigation-Buttons#Log{
            margin-right: 1rem;
        }

        

        /* Hero */
        .Hero-Section{
            padding: 5rem 8rem;
        }

        .Hero-Text-Container{
            text-align: center;
            margin-bottom: 5rem;
            padding: 0rem;
        }
        
        .Hero-Text-Container span{
            color: #1ABC00;
        }
        
        .Hero-Buttons{
            padding-left: 2rem;
            padding-right: 2rem;
        }
        
        .Hero-Image-Container{
            padding: 0rem;
        }
        
        .Hero-Image{
            width: 100%;
        }



        /* Features */
        .Features-Section{
            padding: 5rem 8rem;
        }
        
        .Features-Container h2, p{
            text-align: center;
        }
        
        .Features-Container span{
            color: #6DAEDB;
        }

        .Features-Container .Line-1-Container{
            display: grid;
            justify-items: start;

        }

        .Features-Container .Line-1{
            width: 58%;
        }

        .Features-Container .Line-1 hr{
            width: 100%;
            border: 1px solid #B48FFF;
            margin-top: 0.1rem;
            margin-bottom: 0.3rem;
        }

        .Features-Container .Line-2-Container{
            display: grid;
            justify-items: end;

        }

        .Features-Container .Line-2{
            width: 58%;
        }

        .Features-Container .Line-2 hr{
            width: 100%;
            border: 1px solid white;
            margin-top: 0.1rem;
            margin-bottom: 2rem;
        }

        .Features-List{
            margin-top: 3rem;
        }

        .Features{
            border-radius: 1rem;
        }

        p.Features{
            background-color: #121B2C;
            padding: 1rem;
        }

        

        /* Collections */
        .Collections-Section{
            padding: 5rem 8rem;
        }
        .Collections-Section h2, .Collections-Section h3, .Collections-Section p{
            text-align: center;
            color: black;
        }
        
        .Collections-Container{
            
            background-color: #6DAEDB;
            border-radius: 2rem;
            padding: 3.5rem;
        } 
        .Collections-Boxes-Container{
            margin-top: 2rem;
        }  
        .Collections-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: white;
            border-radius: 1rem;
            margin: 0 1rem;
            display: grid;
            place-items: center;
        }      

        /* Discover */
        .Discover-Section{
            padding: 5rem 8rem;
        }
        .Discover-Section h2, .Discover-Section h3, .Discover-Section p{
            text-align: center;
            color: white;
        }
        
        .Discover-Container{
            
            padding: 3.5rem;
        } 
        .Discover-Boxes-Container{
            margin-top: 2rem;
        }  
        .Discover-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: #121B2C;
            border-radius: 1rem;
            margin: 0 1rem;
            display: grid;
            place-items: center;
        } 
        /* Sharing */
        .Sharing-Section{
            padding: 5rem 8rem 0rem;
        }
        .Sharing-Section h2, .Sharing-Section p{
            text-align: center;
            color: white;
        }
        
        .Sharing-Container{
            
            padding: 3.5rem;
        } 
      
    }





    /* Target Tablets */
    @media screen and (min-width: 700px) and (max-width: 991px) {

        /* Navigation */
        .Navigation-Section{
            padding: 2rem 4rem;
        }

        .Navigation-Logo{
            width: 4rem;
        }

        .Navigation-Buttons{
            padding-left: 2rem;
            padding-right: 2rem;
            border-radius: 2rem;
        }
        
        .Navigation-Buttons#Log{
            margin-right: 1rem;
        }


        /* Hero */
        .Hero-Section{
            padding: 5rem 4rem;
        }
        
        .Hero-Text-Container{
            text-align: center;
            margin-bottom: 5rem;
            padding: 0rem;
        }
        .Hero-Text-Container span{
            color: #1ABC00;
        }
        .Hero-Buttons{
            padding-left: 2rem;
            padding-right: 2rem;
        }
        .Hero-Image-Container{
            padding: 0rem;
        }
        .Hero-Image{
            width: 100%;
        }
        

         /* Features */
         .Features-Section{
            padding: 5rem 4rem;

        }
        
        .Features-Container h2, p{
            text-align: center;
        }
        
        .Features-Container span{
            color: #6DAEDB;
        }

        .Features-Container .Line-1-Container{
            display: grid;
            justify-items: start;

        }

        .Features-Container .Line-1{
            width: 58%;
        }

        .Features-Container .Line-1 hr{
            width: 100%;
            border: 1px solid #B48FFF;
            margin-top: 0.1rem;
            margin-bottom: 0.3rem;
        }

        .Features-Container .Line-2-Container{
            display: grid;
            justify-items: end;

        }

        .Features-Container .Line-2{
            width: 58%;
        }

        .Features-Container .Line-2 hr{
            width: 100%;
            border: 1px solid white;
            margin-top: 0.1rem;
            margin-bottom: 2rem;
        }

        .Features-List{
            margin-top: 3rem;
        }

        .Features{
            border-radius: 1rem;
        }

        p.Features{
            background-color: #121B2C;
            padding: 1rem;
        }


        /* Collections */
        .Collections-Section{
            padding: 5rem 4rem;
        }
        .Collections-Section h2, .Collections-Section h3, .Collections-Section p{
            text-align: center;
            color: black;
        }
        
        .Collections-Container{
            
            background-color: #6DAEDB;
            border-radius: 2rem;
            padding: 2.5rem;
        } 
        .Collections-Boxes-Container{
            margin-top: 2rem;
        }  
        .Collections-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: white;
            border-radius: 1rem;
            margin: 0 1rem;
            
            display: grid;
            place-items: center;
        }      

        /* Discover */
        .Discover-Section{
            padding: 5rem 4rem;
        }
        .Discover-Section h2, .Discover-Section h3, .Discover-Section p{
            text-align: center;
            color:  white;
        }
        
        .Discover-Container{
            
            padding: 2.5rem;
        } 
        .Discover-Boxes-Container{
            margin-top: 2rem;
        }  
        .Discover-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: #121B2C;
            border-radius: 1rem;
            margin: 0 1rem;
            display: grid;
            place-items: center;
        }      

        /* Sharing */
        .Sharing-Section{
            padding: 5rem 4rem 0rem;
        }
        .Sharing-Section h2, .Sharing-Section p{
            text-align: center;
            color: white;
        }
        
        .Sharing-Container{
            
            padding: 2.5rem;
        } 
    }





    /* Phone screens */
    @media screen and (max-width: 699px) {

        /* Navigation */
        .Navigation-Section{
            padding: 1rem 2rem;
            }
        
        .Navigation-Logo{
            width: 2rem;
        }
            
        .Navigation-Buttons{
            border-radius: 1.5rem;
            font-size: 8px;
        }
        
        

        /* Hero */
        .Hero-Container{
            padding: 1rem 1rem;

        }

        .Hero-Text-Container{
            margin-top: 2rem;
            margin-bottom: 2rem;
            padding: 0rem;
        }
        .Hero-Text-Container span{
            color: #1ABC00;
        }

        .Hero-Image-Container{
            padding: 0rem;
        }
        .Hero-Image{
            width: 100%;
        }



        /* Features */
        .Features-Container{
            padding: 2rem 1rem;
        }
        
        .Features-Container h2, p{
            text-align: center;
        }
        
        .Features-Container span{
            color: #6DAEDB;
        }

        .Features-Container .Line-1-Container{
            display: grid;
            justify-items: start;

        }

        .Features-Container .Line-1{
            width: 58%;
        }

        .Features-Container .Line-1 hr{
            width: 100%;
            border: 1px solid #B48FFF;
            margin-top: 0.1rem;
            margin-bottom: 0.3rem;
        }

        .Features-Container .Line-2-Container{
            display: grid;
            justify-items: end;

        }

        .Features-Container .Line-2{
            width: 58%;
        }

        .Features-Container .Line-2 hr{
            width: 100%;
            border: 1px solid white;
            margin-top: 0.1rem;
            margin-bottom: 2rem;
        }

        .Features{
            border-radius: 1rem;
        }

        p.Features{
            background-color: #121B2C;
            padding: 1rem;
        }


         /* Collections */
         .Collections-Section{
            padding: 2rem 1rem;
        }
        .Collections-Section h2, .Collections-Section h3, .Collections-Section p{
            text-align: center;
            color: black;
        }
        
        .Collections-Container{
            
            background-color: #6DAEDB;
            border-radius: 1rem;
            padding: 1.5rem 0.5rem;
        } 
        .Collections-Boxes-Container{
            margin-top: 2rem;
        }  
        .Collections-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: white;
            border-radius: 1rem;
            margin: 0 1rem;
            display: grid;
            place-items: center;
            margin-bottom: 1rem;
        }     
        
        /* Discover */
        .Discover-Section{
            padding: 2rem 1rem;
        }
        .Discover-Section h2, .Discover-Section h3, .Discover-Section p{
            text-align: center;
            color: white;
        }
        
        .Discover-Container{
            padding: 1.5rem 0.5rem;
        } 
        .Discover-Boxes-Container{
            margin-top: 2rem;
        }  
        .Discover-Box{
            padding-top: 1.5rem;
            padding-bottom: 1rem;
            background-color: #121B2C;
            border-radius: 1rem;
            margin: 0 1rem;
            display: grid;
            place-items: center;
            margin-bottom: 1rem;
        }    
        


        /* Sharing */
        .Sharing-Section{
            padding: 2rem 1rem 0rem;
        }
        .Sharing-Section h2, .Sharing-Section p{
            text-align: center;
            color: white;
        }
        
        .Sharing-Container{
            
            padding: 1.5rem;
        } 

    }





    /* General Styling */
    main {
        padding: 0;
    }
    h2, p{
        padding: 0;
    }
    .btn{
        border-radius: 2rem;
    }
    .Navigation-Section{
            border-bottom: solid 2px #434343;
        }

    .Navigation-Logo-Container{
        padding: 0;
    }
    .Navigation-Buttons-Container{
        padding: 0;
        text-align: right;
    }

</style>
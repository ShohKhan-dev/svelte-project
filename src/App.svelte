<script lang="ts">
	import Banner from "./Banner.svelte";
	import About from "./About.svelte";
	import Projects from "./Projects.svelte";
	import Comics from "./Comics.svelte";
</script>

<header class="header_area">
    <div class="main-menu navbar_fixed">
        <nav class="navbar navbar-expand-lg navbar-light ">
            <a class="navbar-brand" href="/"><h3><strong>Shohjahon</strong></h3></a> 
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <div class="mr-auto"></div>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="/">Home </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about-section">about</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#project-section">projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#comic-section">Comic</a>
                    </li>
                   
                    <li class="nav-item">
                        <a class="nav-link" href="https://t.me/SH_Hamrakulov_bot">contact</a>
                    </li>

                </ul>
            </div>
        </nav>
    </div>
</header>
<main class="site-main">

	<Banner/>
	
	<About/>

	<Projects/>

	<Comics/>

</main>

<footer class="mt-auto">
	<div class="container">
		<div class="row">
			<p>
				©2023 Shohjahon
			</p>
		</div>
	</div>
</footer>

<style>


/* Start Footer */

footer {

text-align: center;
font-size: 16px;


}
footer .container {
display: flex;
height: 80px;
align-items: center;
justify-content: center;
}
footer p {
color: rgba(0,0,0,0.5);
margin: 0;
text-align: center;
}

/* End Footer */

</style>
<template>
  <div id="app">
    <header id="header">
		
      
    <!-- Navigation start -->

		<nav class="navbar navbar-custom navbar-fixed-top" role="navigation">

			<div class="container">

				<!-- Brand and toggle get grouped for better mobile display -->
				<div class="navbar-header">
					<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#custom-navbar-collapse-1">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					<a class="navbar-brand" href="#">P.E.E.R. Program ATX</a>
				</div>

				<!-- Collect the nav links, forms, and other content for toggling -->
				<div class="collapse navbar-collapse" id="custom-navbar-collapse-1">
					<ul class="nav navbar-nav navbar-right">
						<li><a href="#intro">Home</a></li>
						<li><a href="#services">Services</a></li>
						<li><a href="#about-header">About</a></li>
						<li><a href="#team-header">Team</a></li>
						<li><a href="#contact-header">Contact</a></li>						
					</ul>
				</div>

			</div>

		</nav>

		<!-- Navigation end -->
    </header>
    <router-view/>
    <footer id="footer">
		
      <!-- Footer start -->
		<footer id="footer">

			<div class="container">

				<div class="row">

					<div class="col-md-12">
						<p class="copy">
							© 2019 P.E.E.R. Program ATX, All Rights Reserved.
						</p>
					</div>

				</div><!-- .row -->

			</div><!-- .container -->

		</footer>

		<!-- Footer end -->
    </footer>
  </div>
</template>

<script>
    export default {
		metaInfo: {
			link: [
				{rel: 'canonical', href: 'https://www.peer-program-atx.com/home'}
			]
		}
        
    }
</script>
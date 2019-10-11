<template>
    <div>
        <!-- Contact section start -->

		<section id="contact-header" class="section-header">

			<div class="color-overlay">

				<div class="container">

					<div class="row">

						<div class="col-sm-12 wow bounceInDown">
							<h2>Contact Us</h2>
							<p>Drop us a line or give us a call. We would love to hear from you.</p>
						</div>

					</div>

				</div>

			</div>

		</section>

		<!-- Contact-data section start -->

		<section id="contact-data" class="callout-light">

			<div class="container">

				<div class="row">

					<div class="col-sm-4 wow bounceInLeft">
						<div class="service">
							<div class="icon">
								<i class="fa fa-envelope-o"></i>
							</div>
							<h4>Mails</h4>
							<div class="text">
								<address>
									<a href="mailto:#">first.last@example.com</a><br/>
									<a href="mailto:#">second.last@example.com</a>
								</address>
							</div>
						</div>
					</div>

					<div class="col-sm-4 wow bounceInUp">
						<div class="service">
							<div class="icon">
								<i class="fa fa-phone"></i>
							</div>
							<h4>Phones</h4>
							<div class="text">
								<address>
									<abbr title="Phone">P:</abbr> (123) 456-7890<br/>
									<abbr title="Phone">P:</abbr> (321) 654-0987<br/>
								</address>
							</div>
						</div>
					</div>

					<div class="col-sm-4 wow bounceInRight">
						<div class="service">
							<div class="icon">
								<i class="fa fa-map-marker"></i>
							</div>
							<h4>Address</h4>
							<div class="text">
								<address>
									121 Somewhere Ave, Suite 123<br/>
									San Francisco, CA 12345
								</address>
							</div>
						</div>
					</div>

				</div><!-- .row -->

			</div><!-- .container -->

		</section>

		<!-- Contact-data section end -->

		<section id="contact" class="section">

			<div class="container">

				<div class="row">

					<div class="col-md-6 wow bounceInLeft">

						<h4>Get in touch</h4>
						<form id="contact-form" method="post" role="form">

							<div class="ajax-hidden">

								<div class="form-group">
									<label class="sr-only" for="c_name">Name</label>
									<input type="text" id="c_name" class="form-control" name="c_name" placeholder="Name">
								</div>

								<div class="form-group">
									<label class="sr-only" for="c_email">Email address</label>
									<input type="email" id="c_email" class="form-control" name="c_email" placeholder="E-mail">
								</div>

								<div class="form-group">
									<textarea class="form-control" id="c_message" name="c_message" rows="7" placeholder="Your message"></textarea>
								</div>

								<button type="submit" class="btn btn-custom-1-inverse">
									<i class="fa fa-bullhorn icon-before"></i> Send it
								</button>

							</div>

							<div class="ajax-response"></div><!-- Displays status when submitting form -->

						</form>

					</div><!-- .col -->

					<div class="col-md-6 wow bounceInUp">

						<h4>Additional info</h4>
						<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati, temporibus natus. Fuga at porro nisi explicabo velit, asperiores officia fugit quisquam, dolores neque animi repellat a iste nihil sunt distinctio!</p>
						<hr/>

						<h4>Business Hours</h4>
						<ul class="list-unstyled">
							<li>Mo - Fr: 8am to 6pm</li>
							<li>Sa, Su: 10am to 2pm</li>
						</ul>
						<hr/>

						<h4>Follow us</h4>
						<ul class="icons-widget">
							<li><a href="#"><i class="fa fa-facebook fa-fw"></i></a></li>
							<li><a href="#"><i class="fa fa-github-alt"></i></a></li>
							<li><a href="#"><i class="fa fa-dribbble"></i></a></li>
							<li><a href="#"><i class="fa fa-google-plus"></i></a></li>
						</ul>

					</div><!-- .col -->

				</div><!-- .row -->

			</div><!-- .container -->

		</section>

		<!-- Contact section end -->

        <!-- Google Map section start-->

		<section id="map-section">

			<div id="map" class="wow flipInX"></div>

		</section>

		<!-- Google Map section end -->
    </div>
</template>

<script>
    export default {
        
    }
</script>
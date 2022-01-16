<script>
	import { onMount } from 'svelte';

	onMount(() => {
		window.jQuery(document).ready(function (e) {
			jQuery('.slider')
				.not('.slick-initialized')
				.slick({
					infinite: true,
					autoplay: true,
					autoplaySpeed: 2000,
					slidesToShow: 3,
					slidesToScroll: -1,
					dots: false,
					arrows: true,
					responsive: [
						{
							breakpoint: 767,
							settings: {
								slidesToShow: 1,
								slidesToScroll: -1
							}
						}

						// You can unslick at a given breakpoint now by adding:
						// settings: "unslick"
						// instead of a settings object
					]
				});
		});
	});
</script>

<div class="service">
	<div class="container">
		<div class="service-in">
			<h3>OUR SERVICES</h3>
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
				labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
				laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
				voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
				cupidatat non proident, sunt in culpa qui officia deserunt mollit.
			</p>
			<div class="property">
				<div class="property-in">
					<ul class="clearfix slider">
						<li>
							<div class="manage">
								<div class="manage-in">
									<img src="images/img1.png" width="523" height="321" alt="img1" />
									<h6>Property Management</h6>
								</div>
							</div>
						</li>
						<li>
							<div class="manage">
								<div class="manage-in">
									<img src="images/img2.png" width="523" height="321" alt="img2" />
									<h6>Property Investment</h6>
								</div>
							</div>
						</li>
						<li>
							<div class="manage">
								<div class="manage-in">
									<img src="images/img3.png" width="523" height="321" alt="img3" />
									<h6>Mortgage Advisor</h6>
								</div>
							</div>
						</li>
					</ul>
				</div>
			</div>

			<a href="#!">More Services</a>
		</div>
	</div>
</div>

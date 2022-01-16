<script>
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';

	const options = {
		type: 'slide',
		pagination: false,
		arrows: false,
		perPage: 3,
		drag: false,
		gap: '2rem',
		breakpoints: {
			767: {
				perPage: 1,
				drag: true,
				gap: '0rem'
			},
			1024: {
				perPage: 2,
				drag: true,
				gap: '0rem'
			},
			1400: {
				gap: '1rem'
			}
		}
	};
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
						<Splide {options}>
							<SplideSlide>
								<li style="width: 100%">
									<div class="manage">
										<div class="manage-in">
											<img src="images/img1.png" width="523" height="321" alt="img1" />
											<h6>Property Management</h6>
										</div>
									</div>
								</li>
							</SplideSlide>

							<SplideSlide>
								<li style="width: 100%">
									<div class="manage">
										<div class="manage-in">
											<img src="images/img2.png" width="523" height="321" alt="img2" />
											<h6>Property Investment</h6>
										</div>
									</div>
								</li>
							</SplideSlide>

							<SplideSlide>
								<li style="width: 100%">
									<div class="manage">
										<div class="manage-in">
											<img src="images/img3.png" width="523" height="321" alt="img3" />
											<h6>Mortgage Advisor</h6>
										</div>
									</div>
								</li>
							</SplideSlide>
						</Splide>
					</ul>
				</div>
			</div>

			<a href="#!">More Services</a>
		</div>
	</div>
</div>

<script>
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';

	const options = {
		type: 'slide',
		pagination: false,
		arrows: false,
		perPage: 4,
		drag: false,
		gap: '1rem',
		breakpoints: {
			767: {
				perPage: 1,
				drag: true,
				gap: '0rem',
				padding: {
					right: '3rem'
				}
			},
			1024: {
				perPage: 2,
				drag: true,
				gap: '0rem',
				padding: {
					right: '0rem',
					left: '0rem'
				}
			},
			1400: {
				gap: '0rem'
			}
		}
	};
</script>

<div class="fact">
	<div class="container">
		<div class="fact-in">
			<h3>FACTS NUMBERS</h3>
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
				labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
				laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
				voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
				cupidatat non proident, sunt in culpa qui officia deserunt mollit.
			</p>

			<div class="award">
				<div class="award-in">
					<div class="clearfix slider1">
						<Splide {options}>
							<SplideSlide>
								<div style="width: 100%">
									<div class="sale">
										<div class="sale-in">
											<a href="#!"
												><img src="/images/award.png" width="49" height="100" alt="award" /></a
											>
											<span>50+</span>
											<p>AWARDS</p>
										</div>
									</div>
								</div>
							</SplideSlide>

							<SplideSlide>
								<div style="width: 100%">
									<div class="sale">
										<div class="sale-in">
											<a href="#!"
												><img src="/images/star-G.png" width="152" height="102" alt="star-G" /></a
											>
											<span>800+</span>
											<p>GOOGLE REVIEWS</p>
										</div>
									</div>
								</div>
							</SplideSlide>

							<SplideSlide>
								<div style="width: 100%">
									<div class="sale">
										<div class="sale-in">
											<a href="#!"
												><img src="/images/f-img3.png" width="111" height="92" alt="f-img3" /></a
											>
											<span>AED 20Billion</span>
											<p>SALES VALUE</p>
										</div>
									</div>
								</div>
							</SplideSlide>

							<SplideSlide>
								<div style="width: 100%">
									<div class="sale">
										<div class="sale-in">
											<a href="#!"
												><img
													src="/images/house%20(1).png"
													width="106"
													height="93"
													alt="house%20(1)"
												/></a
											>
											<span>AED 1 Billion</span>
											<p>LEASING INCOME</p>
										</div>
									</div>
								</div>
							</SplideSlide>
						</Splide>
					</div>
				</div>
			</div>

			<div class="real">
				<div class="real-in">
					<h3>DUBAI REAL ESTATE INVESTMENT OPPORTUNITIES WITH DRIVEN PROPERTIES</h3>
					<p>
						Driven Properties is one of the most prestigious and esteemed names in the Dubai real
						estate market. We have the widest variety of properties in Dubai, from magnificent
						villas and state-of-the-art apartments to the budget options to suit our cost-conscious
						buyers and renters. The Dubai property market has established itself as one of the most
						lucrative and diverse investment options for both Emirati and expat investors. If you
						plan to buy properties in Dubai, Driven Properties is your perfect partner to introduce
						safe, attractive, and thoroughly researched options. By choosing Driven Properties
						amongst the many real estate brokerages in Dubai, you can rest comfortably knowing that
						you are dealing with a company with an impeccable reputation and a long trail of
						testimonials. Driven properties catalogue includes properties for sale in the popular
						areas and secure communities. If you are seeking for Dubai properties investment, then
						look no further than Driven Properties to meet and exceed your needs.
					</p>
				</div>
			</div>
		</div>
	</div>
</div>

<script>
	let activeTab = 't1';
</script>

<div class="popular">
	<div class="container">
		<div class="popular-main">
			<h2>POPULAR DUBAI AREAS</h2>
			<p>
				Select an apartment, villa or office according to your budget and requirements in the Dubai
				areas of your choice. Our wide database of <br />property listings makes it a hassle-free
				process for you. Whether it’s Arabian Ranches, Downtown, JLT, or Jumeirah, we can help you
				find your<br />
				dream home in Dubai.
			</p>
			<div class="tab">
				<div class="tab_links">
					<ul>
						<li class={activeTab === 't1' ? 'active' : ''}>
							<a href="#!" id="t1" on:click={() => (activeTab = 't1')}>BLUEWATERS ISLAND</a>
						</li>
						<li class={activeTab === 't2' ? 'active' : ''}>
							<a href="#!" id="t2" on:click={() => (activeTab = 't2')}>PORT DE LA MER</a>
						</li>
						<li class={activeTab === 't3' ? 'active' : ''}>
							<a href="#!" id="t3" on:click={() => (activeTab = 't3')}>CITY WALK</a>
						</li>
						<li class={activeTab === 't4' ? 'active' : ''}>
							<a href="#!" id="t4" on:click={() => (activeTab = 't4')}>DOWNTOWN</a>
						</li>
					</ul>
				</div>

				<div class="tab_cnt_wrapper">
					<div class="bluewater t1 tab-anime {activeTab === 't1' ? 'show-tab' : 'hide-tab'}">
						<figure>
							<img
								src="/images/bluewaterbg/850x565_0013_Blue%20Waters.png"
								alt="bluewaterbg"
								width="1640"
								height="629"
							/>
						</figure>
						<div class="bluewater-in">
							<h3>Bluewaters Island</h3>
							<p>Where city life meets nature</p>
							<a href="#!">Learn More</a>
						</div>
					</div>
					<div class="bluewater t2 tab-anime {activeTab === 't2' ? 'show-tab' : 'hide-tab'}">
						<figure>
							<img
								src="/images/bluewaterbg/850x565_0013_Blue%20Waters.png"
								alt="bluewaterbg"
								width="1640"
								height="629"
							/>
						</figure>
						<div class="bluewater-in">
							<h3>Port de la mer</h3>
							<p>Where city life meets nature</p>
							<a href="#!">Learn More</a>
						</div>
					</div>
					<div class="bluewater t3 tab-anime {activeTab === 't3' ? 'show-tab' : 'hide-tab'}">
						<figure>
							<img
								src="/images/bluewaterbg/850x565_0013_Blue%20Waters.png"
								alt="bluewaterbg"
								width="1640"
								height="629"
							/>
						</figure>
						<div class="bluewater-in">
							<h3>City Walk</h3>
							<p>Where city life meets nature</p>
							<a href="#!">Learn More</a>
						</div>
					</div>
					<div class="bluewater t4 tab-anime {activeTab === 't4' ? 'show-tab' : 'hide-tab'}">
						<figure>
							<img
								src="/images/bluewaterbg/850x565_0013_Blue%20Waters.png"
								alt="bluewaterbg"
								width="1640"
								height="629"
							/>
						</figure>
						<div class="bluewater-in">
							<h3>Downtown</h3>
							<p>Where city life meets nature</p>
							<a href="#!">Learn More</a>
						</div>
					</div>
				</div>
			</div>
			<div class="bat">
				<figure>
					<img src="/images/1.png" alt="1" width="372" height="234" />
				</figure>
				<div class="bat-in">
					<h3>Bluewaters Island</h3>
					<p>Where city life meets nature</p>
				</div>
			</div>
			<div class="bat">
				<figure>
					<img src="/images/2.png" alt="2" width="372" height="234" />
				</figure>
				<div class="bat-in">
					<h3>PORT DE LA MER</h3>
					<p>Where city life meets nature</p>
				</div>
			</div>
			<div class="bat">
				<figure>
					<img src="/images/3.png" alt="3" width="372" height="234" />
				</figure>
				<div class="bat-in">
					<h3>CITY WALK</h3>
					<p>Where city life meets nature</p>
				</div>
			</div>
			<div class="bat">
				<figure>
					<img src="/images/4.png" alt="4" width="372" height="234" />
				</figure>
				<div class="bat-in">
					<h3>DOWNTOWN</h3>
					<p>Where city life meets nature</p>
				</div>
			</div>

			<a href="#!" class="area">More Areas</a>
		</div>
	</div>
</div>

<style>
	.show-tab {
		opacity: 1;
		visibility: visible;
	}

	.tab-anime {
		transition: all 0.3s ease-in-out;
		position: absolute;
	}

	.hide-tab {
		opacity: 0;
		visibility: hidden;
	}

	.tab_cnt_wrapper {
		overflow: hidden;
		height: 675px;
		position: relative;
	}
</style>

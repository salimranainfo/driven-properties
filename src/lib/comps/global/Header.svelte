<script>
	import { onMount } from 'svelte';
	import { direction } from '$lib/store/index';

	onMount(() => {});

	const menu = [
		{
			text: 'DRIVEN FORBES',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		},
		{
			text: 'SALES',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		},
		{
			text: 'RENTALS',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		},
		{
			text: 'EXPLORE',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		},
		{
			text: 'MARKET TRENDS',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		},
		{
			text: 'ABOUT US',
			link: '#!',
			subMenu: [
				{
					text: 'Buy Ready Property',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Off Plan',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Buy Plots',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Commercial',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				},
				{
					text: 'Seller',
					link: '#!',
					subMenu: [
						{
							text: 'Ready Apartments',
							link: '#!'
						},
						{
							text: 'Ready Villas',
							link: '#!'
						},
						{
							text: 'Ready Townhouses',
							link: '#!'
						}
					]
				}
			]
		}
	];

	let activeMenu = '';
	let activeSubMenu = '';

	const onChangeLang = (dir) => {
		$direction = dir;
	};
</script>

<header>
	<button title="button" class="menu_icon">
		<span />
		<span />
		<span />
	</button>

	{#if $direction === 'ltr'}
		<div class="header-lft">
			<a href="#!">
				<img src="images/Group%20973.png" alt="Group%20973" width="155" height="40" />
			</a>
		</div>
	{/if}

	<div class={`header-rgt ${$direction === 'rtl' && 'demo'}`}>
		<div class="header-in">
			<div class="search">
				<span class={`dpx-header-search-box dpx-show ${$direction === 'rtl' && 'arch'}`}>
					<img src="images/search-zoom-2.png" id="idHeaderZoom" alt="Search" title="Search" />
				</span>
			</div>

			<nav class={`${$direction === 'rtl' && 'demo'}`}>
				<ul class="clearfix">
					{#each menu as item}
						<li>
							<a
								href={item.link}
								class="menu1"
								on:click={() =>
									(activeMenu === item.text ? (activeMenu = '') : (activeMenu = item.text))(
										(activeSubMenu = '')
									)}>{item.text}</a
							>
							<div
								class="subMenu menu-anime {activeMenu === item.text ? 'show-menu' : 'hide-menu'}"
							>
								<ul class="clearfix">
									{#each item.subMenu as subItem}
										<li>
											<a
												href={subItem.link}
												class="menu"
												on:click={() =>
													activeSubMenu === item.text + '-' + subItem.text
														? (activeSubMenu = '')
														: (activeSubMenu = item.text + '-' + subItem.text)}>{subItem.text}</a
											>
											<div
												class="sub menu-anime {activeSubMenu === item.text + '-' + subItem.text
													? 'show-menu'
													: 'hide-menu'}"
											>
												<ul class="clearfix">
													{#each subItem.subMenu as subSubItem}
														<li>
															<a href={subSubItem.link}>{subSubItem.text}</a>
														</li>
													{/each}
												</ul>
											</div>
										</li>
									{/each}
								</ul>
							</div>
						</li>
					{/each}
				</ul>
			</nav>

			<div class={`icons ${$direction === 'rtl' && 'demo'}`}>
				<a href="#!">
					<i class="fa fa-phone" aria-hidden="true" />
				</a>
				<a href="#!" class="mid"><i class="fa fa-whatsapp" aria-hidden="true" /></a>
				<span style="cursor: pointer;" on:click={() => onChangeLang('ltr')}>fr</span>
				<small style="cursor: pointer;" on:click={() => onChangeLang('rtl')}>عربي</small>
			</div>
		</div>
		<div class="menu-icons">
			<div class="search1 mole">
				<span class="dpx-header-search-box dpx-show">
					<img src="images/search-zoom-2.png" id="idHeaderZoom" alt="Search" title="Search" />
				</span>
			</div>
			<div class={`icons mole ${$direction === 'rtl' && 'demo'}`}>
				<span style="cursor: pointer;" on:click={() => onChangeLang('ltr')}>fr</span>
				<small style="cursor: pointer;" on:click={() => onChangeLang('rtl')}>عربي</small>
			</div>
		</div>
	</div>

	{#if $direction === 'rtl'}
		<div class="header-lft demo">
			<a href="#!">
				<img src="images/Group%20973.png" alt="Group%20973" width="155" height="40" />
			</a>
		</div>
	{/if}

	<div class="clear" />

	<div class="dpx-search-area-floating-0">
		<div id="id-search-area-floating" class="dpx-show">
			<div class="row">
				<div class="">
					<div class="dpx-search-area-floating">
						<div class="dpx-search-area-close">
							<i class="fa fa-times" aria-hidden="true" />
						</div>
						<div class="dpx-search-area-tabs">
							<form
								id="frmSearchi"
								name="frmSearchi"
								action="https://www.drivenproperties.com/find/listings"
								method="post"
							>
								<input type="hidden" id="hdby2" name="hdby" value="Sale" />
								<div class="txt">
									<div class="dpx-tab-sale">
										<div class="dpx-search-unit-type active">
											<a href="#!" title="Sale" class="dpx-query-box">For Sale</a>
										</div>
									</div>
									<div class="dpx-tab-rent">
										<div class="dpx-search-unit-type">
											<a href="#!" title="Rent" class="dpx-query-box">For Rent</a>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="search-txt">
										<input
											type="text"
											id="searchTexti"
											name="search"
											class="dpx-search-box dpx-query-input"
											autocomplete="off"
											placeholder="Community or Project"
										/>
										<div id="suggesstion-box-22" />
									</div>
									<ul class="clearfix text-types">
										<li>
											<div class="type">
												<select id="unit-type" name="pty" class="dpx-query-select">
													<option value="">Property Type</option>
													<option value="Apartment">Apartment</option>
													<option value="Bulk Rent Units">Bulk Rent Units</option>
													<option value="Commercial Full Building">Commercial Full Building</option>
													<option value="Commercial Villa">Commercial Villa</option>
													<option value="Duplex">Duplex</option>
													<option value="Factory">Factory</option>
													<option value="Full floor">Full floor</option>
													<option value="Hotel">Hotel</option>
													<option value="Hotel Apartment">Hotel Apartment</option>
													<option value="Labour Camp">Labour Camp</option>
													<option value="Land Commercial">Land Commercial</option>
													<option value="Land Mixed Use">Land Mixed Use</option>
													<option value="Land Residential">Land Residential</option>
													<option value="Multiple Sale Units">Multiple Sale Units</option>
													<option value="Office">Office</option>
													<option value="Penthouse">Penthouse</option>
													<option value="Residential Building">Residential Building</option>
													<option value="Retail">Retail</option>
													<option value="Studio">Studio</option>
													<option value="Townhouse">Townhouse</option>
													<option value="Villa">Villa</option>
													<option value="Warehouse">Warehouse</option>
												</select>
											</div>
										</li>
										<li>
											<div class="type">
												<select id="unit-beds" name="beds" class="dpx-query-select">
													<option value="">Bedroom</option>
													<option value="1">1 Bedroom</option>
													<option value="2">2 Bedrooms</option>
													<option value="3">3 Bedrooms</option>
													<option value="4">4 Bedrooms</option>
													<option value="5">5 Bedrooms</option>
													<option value="6">6 Bedrooms</option>
													<option value="7">7 Bedrooms</option>
													<option value="8">8 Bedrooms</option>
													<option value="9">9 Bedrooms</option>
													<option value="10">10 Bedrooms</option>
												</select>
											</div>
										</li>
										<li>
											<div class="type">
												<select name="price" id="unit-price" class="dpx-query-select">
													<option value="">Price</option>
													<option class="dpx-rent-price dpx-hide" value="30000"
														>30,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="40000"
														>40,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="50000"
														>50,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="60000"
														>60,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="70000"
														>70,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="80000"
														>80,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="90000"
														>90,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="100000"
														>100,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="110000"
														>110,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="120000"
														>120,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="130000"
														>130,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="140000"
														>140,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="150000"
														>150,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="160000"
														>160,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="170000"
														>170,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="180000"
														>180,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="190000"
														>190,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="200000"
														>200,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="225000"
														>225,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="250000"
														>250,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="275000"
														>275,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="250000"
														>250,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="300000"
														>300,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="325000"
														>325,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="350000"
														>350,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="375000"
														>375,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="400000"
														>400,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="500000"
														>500,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="750000"
														>750,000 AED/Year</option
													>
													<option class="dpx-rent-price dpx-hide" value="1000000"
														>1,000,000 AED/Year</option
													>
													<option class="dpx-sale-price dpx-show" value="300000">300,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="400000">400,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="500000">500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="600000">600,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="700000">700,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="800000">800,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="900000">900,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1000000"
														>1,000,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1100000"
														>1,100,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1200000"
														>1,200,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1300000"
														>1,300,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1400000"
														>1,400,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1500000"
														>1,500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1600000"
														>1,600,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1700000"
														>1,700,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1800000"
														>1,800,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="1900000"
														>1,900,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="2000000"
														>2,000,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="2250000"
														>2,250,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="2500000"
														>2,500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="2750000"
														>2,750,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="2500000"
														>2,500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="3000000"
														>3,000,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="3250000"
														>3,250,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="3500000"
														>3,500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="3750000"
														>3,750,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="4000000"
														>4,000,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="5000000"
														>5,000,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="7500000"
														>7,500,000 AED</option
													>
													<option class="dpx-sale-price dpx-show" value="10000000"
														>10,000,000 AED</option
													>
												</select>
											</div>
										</li>
										<li>
											<ul class="clearfix size">
												<li>
													<div class="type1">
														<select name="price" id="unit-price" class="dpx-query-select">
															<option value="">Min Size</option>
															<option class="dpx-rent-price dpx-hide" value="30000"
																>30,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="40000"
																>40,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="50000"
																>50,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="60000"
																>60,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="70000"
																>70,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="80000"
																>80,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="90000"
																>90,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="100000"
																>100,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="110000"
																>110,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="120000"
																>120,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="130000"
																>130,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="140000"
																>140,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="150000"
																>150,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="160000"
																>160,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="170000"
																>170,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="180000"
																>180,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="190000"
																>190,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="200000"
																>200,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="225000"
																>225,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="250000"
																>250,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="275000"
																>275,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="250000"
																>250,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="300000"
																>300,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="325000"
																>325,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="350000"
																>350,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="375000"
																>375,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="400000"
																>400,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="500000"
																>500,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="750000"
																>750,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="1000000"
																>1,000,000 AED/Year</option
															>
															<option class="dpx-sale-price dpx-show" value="300000"
																>300,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="400000"
																>400,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="500000"
																>500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="600000"
																>600,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="700000"
																>700,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="800000"
																>800,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="900000"
																>900,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1000000"
																>1,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1100000"
																>1,100,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1200000"
																>1,200,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1300000"
																>1,300,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1400000"
																>1,400,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1500000"
																>1,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1600000"
																>1,600,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1700000"
																>1,700,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1800000"
																>1,800,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1900000"
																>1,900,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2000000"
																>2,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2250000"
																>2,250,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2500000"
																>2,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2750000"
																>2,750,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2500000"
																>2,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3000000"
																>3,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3250000"
																>3,250,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3500000"
																>3,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3750000"
																>3,750,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="4000000"
																>4,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="5000000"
																>5,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="7500000"
																>7,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="10000000"
																>10,000,000 AED</option
															>
														</select>
													</div>
												</li>
												<li>
													<div class="type2">
														<select name="price" id="unit-price" class="dpx-query-select">
															<option value="">Max Size</option>
															<option class="dpx-rent-price dpx-hide" value="30000"
																>30,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="40000"
																>40,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="50000"
																>50,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="60000"
																>60,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="70000"
																>70,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="80000"
																>80,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="90000"
																>90,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="100000"
																>100,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="110000"
																>110,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="120000"
																>120,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="130000"
																>130,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="140000"
																>140,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="150000"
																>150,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="160000"
																>160,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="170000"
																>170,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="180000"
																>180,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="190000"
																>190,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="200000"
																>200,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="225000"
																>225,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="250000"
																>250,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="275000"
																>275,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="250000"
																>250,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="300000"
																>300,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="325000"
																>325,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="350000"
																>350,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="375000"
																>375,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="400000"
																>400,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="500000"
																>500,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="750000"
																>750,000 AED/Year</option
															>
															<option class="dpx-rent-price dpx-hide" value="1000000"
																>1,000,000 AED/Year</option
															>
															<option class="dpx-sale-price dpx-show" value="300000"
																>300,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="400000"
																>400,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="500000"
																>500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="600000"
																>600,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="700000"
																>700,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="800000"
																>800,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="900000"
																>900,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1000000"
																>1,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1100000"
																>1,100,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1200000"
																>1,200,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1300000"
																>1,300,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1400000"
																>1,400,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1500000"
																>1,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1600000"
																>1,600,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1700000"
																>1,700,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1800000"
																>1,800,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="1900000"
																>1,900,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2000000"
																>2,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2250000"
																>2,250,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2500000"
																>2,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2750000"
																>2,750,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="2500000"
																>2,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3000000"
																>3,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3250000"
																>3,250,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3500000"
																>3,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="3750000"
																>3,750,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="4000000"
																>4,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="5000000"
																>5,000,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="7500000"
																>7,500,000 AED</option
															>
															<option class="dpx-sale-price dpx-show" value="10000000"
																>10,000,000 AED</option
															>
														</select>
													</div>
												</li>
											</ul>
										</li>
									</ul>
									<ul class="clearfix btns">
										<li>
											<div class="map">
												<a href="#!">Map View</a>
											</div>
										</li>
										<li>
											<div class="">
												<button type="submit" class="btn btn-block">Search</button>
											</div>
										</li>
									</ul>
								</div>
							</form>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</header>

<style>
	.show-menu {
		/* opacity: 1; */
		/* max-height: 500px; */
		visibility: visible;
		/* overflow: auto; */
	}

	.menu-anime {
		transition: all 0.5s ease-in-out;
	}

	.hide-menu {
		/* overflow-y: hidden; */
		opacity: 0;
		/* max-height: 0; */
		visibility: hidden;
	}
</style>

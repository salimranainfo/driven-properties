<script>
	import '$lib/assets/css/style.css';
	import '@splidejs/splide/dist/css/splide.min.css';

	import Footer from '$lib/comps/global/Footer.svelte';
	import Header from '$lib/comps/global/Header.svelte';

	import { direction } from '$lib/store/index';
	import { onMount } from 'svelte';

	let setDirAttrOnHtmlTag = () => {};

	$: setDirAttrOnHtmlTag($direction);

	onMount(() => {
		setDirAttrOnHtmlTag = (dir) => {
			if (window) {
				if (dir === 'rtl') {
					document.querySelector('html').setAttribute('dir', 'rtl');
				} else {
					document.querySelector('html').removeAttribute('dir');
				}
			}
		};
	});
</script>

<Header />
<slot />
<Footer />

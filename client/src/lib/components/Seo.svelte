<script type="ts">
	import { page } from '$app/stores';
	const brand = 'SteinBock500';
	export let title = brand;
	export let description =
		'SteinBock500 Helps Those Who Help Each Other Into Freedom, Justice, Love and Peace.';
	export let image =
		'https://github.com/user-attachments/assets/6c4af7cf-3c5c-4b45-8230-28eb95791d8b';
	export let url = `https://${$page.url.host}${$page.url.pathname}`;
</script>

<svelte:head>
	<title>{title} - {brand}</title>
	<meta name="description" content={description} />
	<meta property="og:type" content="website" />
	<meta property="og:title" content={`${title} - ${brand}`} />
	<meta property="og:site_name" content={brand} />
	<meta property="og:description" content={description} />
	<meta property="og:image" name="og:image" content={image} />
	<meta name="og:url" content={url} />
	<meta name="twitter:image" content={image} />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={`${title} - ${brand}`} />
	<meta name="twitter:description" content={description} />
</svelte:head>

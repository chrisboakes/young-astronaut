<script>
	import Recordings from '../components/Recordings.svelte';
	import Biography from '../components/Biography.svelte';
	import Band from '../components/Band.svelte';
	import Social from '../components/Social-Media.svelte';
	import Videos from '../components/Videos.svelte';
</script>

<svelte:head>
	<title>Young Astronaut Band</title>
	<meta name="description" content="Official website for British indie band Young Astronaut. Featuring music, videos and information.">
	<meta property="og:title" content="Young Astronaut - Official Website">
	<meta property="og:description" content="Official website for British indie band Young Astronaut. Featuring music, videos and information.">
	<meta property="og:url" content="https://youngastronaut.co.uk/">
	<meta property="og:site_name" content="Young Astronaut">
	<meta property="og:image" content="https://youngastronaut.co.uk/og-image.jpg">
	<meta content="summary" name=twitter:card>
	<meta name="twitter:title" content="Young Astronaut - Official Website">
	<meta name="twitter:description" content="Official website for British indie band Young Astronaut. Featuring music, videos and information.">
	<meta name="twitter:domain" content="youngastronaut.co.uk">
	<meta name="twitter:image:src" content="https://youngastronaut.co.uk/twitter-image.jpg">
	<meta name="twitter:image:alt" content="Young Astronaut Band Photo">
</svelte:head>

<Recordings />

<Biography />

<Band />

<Videos />

<Social />

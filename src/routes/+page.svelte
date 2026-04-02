<script>
    import image from "$lib/assets/profile.jpg"
    let title = "(@dmaltzi) • Instagram profile";
    let description = "435 Followers, 3,267 Following, 120 Posts - See Instagram photos and videos from (@dmaltzi)";
    let url = "https://instagram.dmaltzi.com/"
</script>

<svelte:head>
    <title>{title}</title>
    <meta name="title" content={title}>
    <meta name="description" content={description} />
    <meta property="og:type" content="website" />
    <meta property="og:url" content={url} />
    <meta property="og:title" content={title} />
    <meta property="og:description" content={description} />
    <meta property="og:image" content={image}/>  
    <meta property="og:type" content="website" />
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

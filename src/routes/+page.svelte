<script>
    let title = "(@dmaltzi) • Instagram profile";
    let description = "435 Followers, 3,267 Following, 120 Posts - See Instagram photos and videos from (@dmaltzi)";
    let rickroll = "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
    let url = "https://instagram.dmaltzi.com"
    let profile = "/profile.jpg"
    let imageUrl = url + profile
    $effect(() => {
        setTimeout(() => {
            window.location.href = rickroll;
        }, 500);
    })
</script>

<svelte:head>
    <title>{title}</title>
    <meta name="title" content={title}>
    <meta name="description" content={description} />
    <meta property="og:type" content="website" />
    <meta property="og:url" content={url} />
    <meta property="og:title" content={title} />
    <meta property="og:description" content={description} />
    <meta property="og:image" content={imageUrl} />
    
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:title" content={title} />
    <meta name="twitter:description" content={description} />
    <meta name="twitter:image" content={imageUrl} />
</svelte:head>

<div style="font-family: sans-serif; display: flex; justify-content: center; align-items: center; height: 100vh;">
    <p>Redirecting to Instagram...</p>
</div>

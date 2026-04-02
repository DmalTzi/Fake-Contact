<script>
    let title = "(@dmaltzi) • Instagram profile";
    let description = "435 Followers, 3,267 Following, 120 Posts - See Instagram photos and videos from (@dmaltzi)";
    let rickroll = "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
    let url = "https://instagram.dmaltzi.com"
    let profile = "/profile.jpg"
    let image = url + profile
    $effect(() => {
        setTimeout(() => {
            window.location.href = rickroll;
        }, 250);
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
    <meta property="og:image" content={image}/>
    <meta property="twitter:url" content={url} />
    <meta property="twitter:title" content={title} />
    <meta property="twitter:description" content={description} />
    <meta property="twitter:image" content={image}>
    </svelte:head>

<div style="font-family: sans-serif; display: flex; justify-content: center; align-items: center; height: 100vh;">
    <p>Redirecting to Instagram...</p>
</div>

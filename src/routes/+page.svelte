<script>
  let title = "สอนทำ Svelte SEO ให้ติดหน้าแรก";
  let description = "คู่มือฉบับสมบูรณ์สำหรับการปรับแต่ง SvelteKit ให้เป็นมิตรกับ Google";
</script>

<svelte:head>
  <title>{title}</title>
  <meta name="description" content={description} />
  
  <meta property="og:title" content={title} />
  <meta property="og:description" content={description} />
  <meta property="og:type" content="website" />
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

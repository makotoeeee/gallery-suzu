<script>
    const urls = [
        "https://images.dog.ceo/breeds/shiba/shiba-11.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-12.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-14.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-17.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-2.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-3i.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-4.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-5.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-6.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-7.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-8.jpg",
        "https://images.dog.ceo/breeds/shiba/shiba-9.jpg",
    ];
</script>

{#each urls as url}
    <img src={url} alt="cute dog!" />
{/each}

<style>
    img{
        max-width: 100%;
        height: auto;
        padding: 0;
        margin: 0;
    }
</style>
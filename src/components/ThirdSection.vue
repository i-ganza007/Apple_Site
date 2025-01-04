<template>
    <section id="thirdSection">
        <div class="content_section">
            <img src="https://www.apple.com/v/home/bx/images/logos/apple-watch-series-10/hero_logo_apple_watch_series_10__dla4dkv1wfue_largetall.png" alt="watch-logo">
            <p>Thinstant classic.</p>
            <div class="button-group">
                <button>Learn more</button>
                <button>Buy</button>
            </div>
        </div>
    </section>
</template>
<script setup>

</script>
<style scoped>
.content_section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    position: relative;
    top: 50px;
    color: white;
    font-size: 35px;
    font-family: -apple-system, BlinkMacSystemFont, sans-serif;
}
.content_section > p{
    color: rgba(0, 0, 0, 0.905);
    font-size: 2rem;
}
</style>
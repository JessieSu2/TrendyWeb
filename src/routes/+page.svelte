<script>
    import Intro from './introduction/+page.svelte';
    import WhyTrendy from './whyTrendy/+page.svelte';
</script>

<div class="container">
    <div class="margin"> 

        <section class="top-container">
            <Intro/>
        </section>
        <section>
            <WhyTrendy/>
        </section>
    </div>
</div>


<style>
    .container{
        padding: 5em;
        background-color:#221911;
        /* height: max-content; */
        font-family: "Gayathri";
        width: auto;
    }
    .margin{
        margin: 5em 5em 5em 5em;
    }
</style>

<link href="https://fonts.googleapis.com/css2?family=Gayathri:wght@100&display=swap" rel="stylesheet">

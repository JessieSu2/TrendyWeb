<!-- <script lang="ts">
    import type { PageData } from './$types';
    
    export let data: PageData;
</script> -->
<script>
    import {IconCoffee} from '@tabler/icons-svelte';
</script>
<div class="container">

    <h1 class="heading SubText">Why Trendy?</h1>
    <div class="grid">
        <div class="grid-column">
            <span class="SubText">Variety</span>
            <p class="text">Stay Trendy</p>
            <div style="vertical-align: middle;">
                <ul class="list text">
                    <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Taste Exploration</li>
                    <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Mood Enhancement</li>
                    <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Seasonal Enjoyment</li>
                    <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Adaptability to Trends</li>
                </ul>
            </div>
        </div>
        <div class="grid-column">
            <span class="SubText">Convenience</span>
            <p class="text">Easy to Use</p>
            <ul class="list text">
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Time-Saving</li>
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Simple & Intuitive</li>
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Favorite Tracking</li>
            </ul>
        </div>
        <div class="grid-column">
            <span class="SubText">Confidence</span>
            <p class="text">Radiate confidence</p>           
            <ul class="list text">
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Helps Reduce Social Anxiety</li>
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Encouraging Exploration</li>
                <li><IconCoffee color="#AE8661" style="padding: 0em 0.5em;"/>Clear Ordering Instructions</li>
            </ul> 
           
        </div>
    </div>
</div>


<style>
    .SubText{
        color: #F5F0EB;
        font-size: var(--h4);
        font-weight: 700;
    }
    .text{
        color: #F5F0EB;
    }
    .container{
        text-align: center;
        width: 100%;
    }
    .heading{
        font-size: 2em;
    }
    .grid{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 50px;
    }
    .grid-column{
        padding: 10px;
        min-width: 300px;
        background-color:#2C2117;
    }
    .list{
        text-align: left;
        display: block;
        list-style: none;
        padding: 0 1em;

    }
    .icon{
        padding: 20px;
    }
</style>


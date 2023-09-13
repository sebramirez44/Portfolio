<style>
    .Title {
        font-family: Roboto;
        font-size:7em;
        font-weight: bold;
        text-align: center;
        margin-top: 5%;
    }

    .animate-fade-in {
        animation: slidein 0.5s linear 0.5s forwards;
    }

    @keyframes slidein {
        from {
            font-size: 7em;
        }
        to {
            font-size: 8em; 
        }
    }
</style>
<script lang="ts">
    export let title:string;
    let fontSize:number = 4;
    import {onMount} from 'svelte';
    function onFirstRender() {
        fontSize = 8;
    }
    onMount(onFirstRender);
</script>
<div class="Title animate-fade-in">
    {title}
</div>
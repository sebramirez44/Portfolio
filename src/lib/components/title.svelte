<style>
    .Title {
        font-family: Roboto;
        font-size:7rem;
        font-weight: bold;
        text-align: center;
        margin-top: 5%;
        
    }

    .animate-fade-in {
        animation: slidein 0.5s linear 0.5s forwards;
    }
    .out {
        height:20vh;
    }

    @keyframes slidein {
        from {
            font-size: 7rem;
        }
        to {
            font-size: 8rem; 
        }
    }
</style>
<script lang="ts">
    export let title:string;
</script>
<div class="out">
    <div class="animate-fade-in Title">
        {title}
    </div>
</div>
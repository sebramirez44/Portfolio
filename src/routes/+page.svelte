<style>
    .containerHome {
        display:flex;
        flex-direction:column;
        width:100%;
        align-items:center;
    }
    .firstBox {
        margin-top:5%;
        display:flex;
        flex-direction:column;
        width:100%;
    }
</style>
<script lang="ts">
    import Title from '../lib/components/title.svelte';
</script>  
<div class="containerHome">
    <Title title="What is this website?"/>
    <!-- maybe hacer esto en un componente, por ahora no se necesita -->
    <div class="firstBox">
        <div class="firstBoxItem">
            
        </div>
    </div>
</div>
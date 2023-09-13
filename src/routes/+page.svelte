<style>
    .containerHome {
        display:flex;
        flex-direction:column;
        width:100%;
        align-items:center;
    }
    .firstBox {
        margin-top:10%;
        display:flex;
        flex-direction:row;
        justify-content:space-between;
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
            <p>ok</p>
        </div>
        <div class="secondBoxItem">
            
        </div>
    </div>
</div>
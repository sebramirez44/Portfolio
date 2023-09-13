
<style>
    .containerHome {
        display:flex;
        flex-direction:column;
        width:100%;
        align-items:center;
    }
    .firstBox {
        margin-top:5%;
    }
</style>
<script lang="ts">
    import Title from '../../lib/components/title.svelte';
</script>  
<div class="containerHome">
    <Title title="Some of what I'm good at."/>
    <!-- maybe hacer esto en un componente, por ahora no se necesita -->
    <div class="firstBox">
        <p>ok</p>
    </div>
</div>
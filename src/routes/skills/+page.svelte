
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
        flex-direction:column;
        justify-content:center;
        align-items:center;
    }
    .Languages {
        display: flex;
        flex-direction:row;
        justify-content:space-evenly;
        margin-bottom:5%;
        flex-wrap:wrap;
        width:80%;
    }
    .titleContent {
        width:80%;
        display:flex;
        flex-direction:column;
        justify-content:space-evenly;
        margin-bottom:10%;
    }
    .subtitle {
        font-size:4em;
        font-family:Roboto;
    }
    .content {
        font-size:1.8em;
        font-family:Montserrat;
        line-height:2em;
    }
</style>
<script lang="ts">
    import Title from '../../lib/components/title.svelte';
</script>
<div class="containerHome">
    <Title title="Some of what I'm good at."/>
    <!-- maybe hacer esto en un componente, por ahora no se necesita -->
    <div class="firstBox">
        <div class="Languages">
            <!-- quitar esto, renderear de una lista de objetos y en hover mostrar nombre y descripcion -->
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em;"/>
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em;"/>
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em;"/>
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em; margin-top:5%;"/>
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em; margin-top:5%;"/>
                <img src="/cpp.jpeg" alt="cpp" width="30%" style="border-radius:2em; margin-top:5%;"/>
        </div>
    </div>
    <div class="titleContent">
        <h1 class="subtitle">How can you know I'm actually good at these technologies?</h1>
        <p class="content">Take a look in the projects tab! it included different projects I've
            made and the technologies involved in each one, some skills might not be represented but a lot will be.
        </p>
    </div>
</div>
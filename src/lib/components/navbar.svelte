
<style>
    nav {
        height: 10vh;
        background-color:#08090A;
        border-bottom: 1px solid #011638;
        display:flex;
        flex-direction:row;
        justify-content:center;
        align-items:center;
        font-family:'Roboto';
    }
    ul {
        margin-top:0;
        padding-top:0;
        display:flex;
        flex-direction:row;
        align-items:center;
        width:50%;   
        justify-content:space-around;
    }
    li {
        /* padding-left:10em; */
        text-decoration:none;
        list-style-type:none;
        display:flex;
        margin-top:1em;
        font-weight:bold;
        font-size:1.2em;
    }
    
    .brand {
        display:flex;
        width:50%;
        padding-left:4%;
        font-weight:bold;
        font-size:1.2em;
    }
    a {
        text-decoration:none;
        color:white;
    }
    .page:hover {
        color:#969696;
    }
    .active {
        color:#969696;
    }
</style>
<script lang="ts">
    export let currentPage:any;
</script>
<nav>
    <!-- <a href="/" class="brand">Sebastian Ramirez</a> -->
    <ul>
        <!-- aqui en class, si esta seleccionado hacerlo en otra clase usar ternary -->
        <!-- <li><a href="/" class={currentPage === "/" ? "active" : "page"}>Home</a></li>
        <li><a href="/skills" class={currentPage === "/skills" ? "active" : "page"}>Skills</a></li>
        <li><a href="/projects" class={currentPage === "/projects" ? "active" : "page"}>Projects</a></li>
        <li><a href="/about" class={currentPage === "/about" ? "active" : "page"}>About Me</a></li> -->
    </ul>
    
</nav>


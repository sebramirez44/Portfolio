<script>
    import '../app.css';
    import Navbar from '../lib/components/navbar.svelte';
    import {page} from '$app/stores';
    // pasar ese store de page como un prop
    console.log();
</script>
<body>
    <Navbar currentPage= {$page.url.pathname.slice($page.url.pathname.lastIndexOf('/'))} />
    <slot/> 
</body>


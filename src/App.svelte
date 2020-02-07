<script>
  import { setContext } from "svelte";
  import { Router }     from "svelte-routing";
  import Nav            from "./Nav.svelte";
  import Contenido      from "./Contenido.svelte";
  
  const URL = {
    articulos :  "https://tiendabackend.herokuapp.com/api/articulos/",
    clientes :   "https://tiendabackend.herokuapp.com/api/clientes/"
  };
  setContext("URL", URL);
</script>

<style>
  
</style>

<Router>
  <Nav />
  <Contenido />
</Router>
<script>
  import {Route} from "svelte-routing";
  import Inicio from "./Inicio.svelte";
  import Articulos from "./Articulos.svelte";
  import Clientes from "./Clientes.svelte";
</script>

<style>
  main {
    border: 1px solid blue;
  }
</style>

<main>
  <Route path="/" component={Inicio} />
  <Route path="/articulos" component={Articulos} />
  <Route path="/clientes" component={Clientes} />
</main>

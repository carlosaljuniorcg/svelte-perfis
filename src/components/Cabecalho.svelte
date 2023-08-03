<script>
    import Formulario from "./Formulario.svelte";
    import Titulo from "./Titulo.svelte";

</script>
<header>
    <Titulo />

    <div class="busca-usuario">
        <Formulario on:aoAlterarUsuario/>
    </div>
</header>
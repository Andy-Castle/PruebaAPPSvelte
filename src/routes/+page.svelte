<script>
import Imagen from '/src/components/imagen.svelte'
import Calculator from '../components/Calculator.svelte';
</script>

<h1>Vamos hacer unas preubas con svelte</h1>
<div class="imagenContainer"><Imagen /></div>

<div class="calculatorContainer"><Calculator/></div>

<style>
    h1{
        text-align: center;
    }
    .calculatorContainer{
        display: flex;
        justify-content: center;
        margin: 10px 0;
    }

</style>


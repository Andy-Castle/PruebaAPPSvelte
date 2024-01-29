<div>
<input type="number" bind:value={num1}>
<input type="number" bind:value={num2}>
<p>{resultado = num1 + num2 || 0}</p>
</div>

<script>
    let num1;
    let num2;
    let resultado;
</script>



<style>
    div{
        display: grid;
        grid-template-columns: 1;
        
    }

    input{
        margin: 10px 0;
    }
</style>
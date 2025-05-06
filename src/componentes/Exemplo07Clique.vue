<!-- SCRIPT -->

<script setup>

    // FUnção
    function mensagem(){
        alert('Trabalhando com eventos de clique!')
    }

</script>

<!-- HTML -->
 <template>
    <button @click="mensagem">Clique aqui</button>
 </template>
<!-- SCRIPT -->
<script setup>
    // Variável
    let validacao = false;
</script>

<!-- CSS -->
<style>
    .ok{color: green}

    .falha{color: red}
</style>

<!-- HTML -->
 <template>
    <p :class="validacao ? 'ok' : 'falha'">Utilizando diretiva class</p>
 </template>
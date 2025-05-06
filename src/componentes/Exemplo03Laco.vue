<!-- SCRIPT -->
<script setup>  
    // Vetor
    let nomes = ["Ana", "Bia", "Carlos", "Daniel", "Eduarda", "Fernanda", "Gabriel", "Henrique", "Isabel", "João"];
</script>

<!-- HTML -->
 <template>
    <ul>
        <li v-for="nome in nomes">{{ nome }}</li>
    </ul>
 </template>
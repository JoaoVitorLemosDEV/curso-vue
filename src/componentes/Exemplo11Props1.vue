<!-- SCRIPT -->
<script setup>

    // Importar componente
    import Exemplo11Props2 from './Exemplo11Props2.vue';

    // Variáveis
    let cidade = 'Vitória da Conquista';
    let cidades = ['Vitória da Conquista', 'Salvador', 'São Paulo', 'Rio de Janeiro'];

    // Função
    function mensagem() {
        alert('Função criada no componente: Exemplo11Props1');
    }
</script>

<!-- HTML -->
 <template>
    <Exemplo11Props2 nome="João" idade="20" :cidade="cidade" :vetor="cidades" :funcao="mensagem"></Exemplo11Props2>
 </template>
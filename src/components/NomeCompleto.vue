<template>
    <div>
        <Rotulo nome="Nome">
            <input type="text" v-model="usuario.nome"/>
        </Rotulo>
        <Rotulo nome="Sobrenome">
            <input type="text" v-model="usuario.sobrenome"/>
        </Rotulo>
    </div>
</template>

<script>
import Rotulo from '@/components/Rotulo'

export default {
    props: ['usuario', 'nome', 'sobrenome'],

    components:{
        'Rotulo': Rotulo
    }
}
</script>

<style>

</style>

<template>
ola
<ImagemPrincipal/>
<br>
<VideoUnico/>
<br>
<TabelasDiversos/>
<br>
<Outro/>
</template>

<script>
import ImagemPrincipal from '@/components/ImagensDiversas.vue'
import VideoUnico from './VideoUnico.vue'
import Outro from './Outro.vue'
export default {
    name: 'PaginaPrincipal',
    components: {
        ImagemPrincipal, VideoUnico, Outro
    },
}
</script>
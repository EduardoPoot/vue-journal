<template>
    <div class="d-flex justify-content-center">
        <h1 class="align-self-center">
            Nada seleccionado
        </h1>
    </div>
    <FabComponent/>
</template>

<script>
import { defineAsyncComponent } from "vue";

export default {
    name      : "NoEntrySelected",
    components: {
        FabComponent: defineAsyncComponent(() => import('@/modules/daybook/components/FabComponent'))
    }
}
</script>

<style scoped lang="scss">
div {
  height: 100%;
}
</style>
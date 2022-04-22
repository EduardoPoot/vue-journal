<template>
    <div class="mb-3 pointer p-2 entry-container" @click="$router.push({name:'entry',params:{id:10}})">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">21</span>
            <span class="mx-1 fs-5">abril</span>
            <span class="mx-2 fw-light">2021</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt ipsam quibusdam reprehenderit sunt?
            Aperiam blanditiis delectus eaque in incidunt inventore, ipsum minus nobis possimus quasi quibusdam quisquam
            repellendus, temporibus vel.
        </div>
    </div>
</template>

<script>
export default {
    name: "EntryComponent"
}
</script>

<style scoped lang="scss">
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
}
</style>
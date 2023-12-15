<template>
  <VRow>
    <VCol v-for="n in 205" :key="n" cols="2">
      <VCard>
        <VImg
          :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
          aspect-ratio="1"
          cover
        >
          <template v-slot:placeholder></template>
        </VImg>
      </VCard>
    </VCol>
  </VRow>
</template>
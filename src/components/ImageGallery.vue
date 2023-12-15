<template>
  <VRow>
    <VCol v-for="n in 205" :key="n" cols="2">
      <VCard>
        <VImg
          :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
          aspect-ratio="1"
          cover
        >
          <template v-slot:placeholder>
            <VRow class="fill-height ma-0" align="center" justify="center">
              <v-progress-circular
                indeterminate
                color="grey-lighten-5"
              ></v-progress-circular
            ></VRow>
          </template>
        </VImg>
      </VCard>
    </VCol>
  </VRow>
</template>
<template>
  <VCard class="mx-5 my-3 pa-3">
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
                <VProgressCircular
                  indeterminate
                  color="grey-lighten-5"
                ></VProgressCircular
              ></VRow>
            </template>
          </VImg>
        </VCard>
      </VCol>
    </VRow>
  </VCard>
</template>

  <template>
  <VCARD>
    <v-footer class="d-flex flex-column">
      <div class="bg-teal d-flex w-100 align-center px-4">
        <strong>Get connected with us on social networks!</strong>

        <v-spacer></v-spacer>

        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          :icon="icon"
          variant="plain"
          size="small"
        ></v-btn>
      </div>

      <div class="px-6 py-6 bg-white text-center w-100">
        {{ new Date().getFullYear() }} — <strong>Image Gallery</strong>
      </div>
    </v-footer>
  </VCARD>
</template>
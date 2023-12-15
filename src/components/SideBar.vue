<template>
  <VNavigationDrawer expand-on-hover rail>
    <VList>
      <VListItem
        prepend-avatar="https://randomuser.me/api/portraits/women/85.jpg"
        title="Elissa Perry"
        subtitle="EPerry123@gmailcom"
      ></VListItem>
    </VList>
    <VDivider />
    <VList density="compact" nav>
      <VListItem
        prepend-icon="mdi-image"
        title="Color Gallery"
        value="Color Gallery"
      />
      <VListItem prepend-icon="mdi-dialpad" title="More" value="More" />
    </VList>
  </VNavigationDrawer>
</template>
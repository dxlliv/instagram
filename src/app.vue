<template>
  <v-app>
    <suspense>
      <AppLoader>
        <NuxtLayout>
          <NuxtPage />
        </NuxtLayout>
      </AppLoader>
    </suspense>
  </v-app>
</template>

<style lang="scss">

</style>

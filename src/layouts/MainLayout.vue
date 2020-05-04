<template>
  <q-layout view="lHh Lpr lfr ">
    <q-header unelevated></q-header>
    <q-footer unelevated class="app-footer q-mx-xl">
      <q-toolbar>
        <q-toolbar-title>All rights reserved @ Loren's Cafe 2020</q-toolbar-title>
        <div class="q-gutter-md">
          <q-icon name="mdi-facebook" size="sm" color="primary"></q-icon>
          <q-icon name="mdi-instagram" size="sm" color="primary"></q-icon>
          <q-icon name="mdi-linkedin" size="sm" color="primary"></q-icon>
          <q-icon name="mdi-twitter" size="sm" color="primary"></q-icon>
        </div>
      </q-toolbar>
    </q-footer>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: "MainLayout",
  data() {
    return {};
  }
};
</script>

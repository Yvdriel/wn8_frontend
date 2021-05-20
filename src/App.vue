<template>
  <q-layout view="lHh Lpr lFf" class="bg-grey-9 text-grey-1">
    <q-header elevated class="header">
      <q-toolbar>
        <q-toolbar-title>
          Wn8stats
        </q-toolbar-title>
        <q-tabs class="header__tabs">
          <q-route-tab to="/" label="Home" exact/>
          <q-route-tab to="/about" label="Our Mission" />
          <q-route-tab to="/about" label="Developer" />
          <q-route-tab to="/about" label="Support Us" />
          <q-route-tab to="/about" label="About" />
        </q-tabs>
        <div>
        </div>
      </q-toolbar>

    </q-header>
    <q-page-container class="layout">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

export default {
  name: 'LayoutDefault',

  components: {
  },

  data () {
    return {
    }
  }
}
</script>

<style lang="sass">
::-webkit-scrollbar
  width: 7px
  background: rgba(0, 0, 0, 0.4)
::-webkit-scrollbar-thumb
  border-radius: 20px
  background: rgba(150, 150, 150, 0.6)
::-webkit-scrollbar-track
  background: rgba(0, 0, 0, 0.6)


.layout
  width: 90%
  margin: 0 auto
.header
  background-color: rgba(0, 0, 0, 0.6) !important
</style>

<template>
  <b-container>
    <h1>Settings</h1>
    <settings-exporter/>
  </b-container>
</template>

<script>
import SettingsExporter from '@/components/settings/SettingsExporter.vue'

export default {
  name: 'Settings',
  components: { SettingsExporter }
}
</script>

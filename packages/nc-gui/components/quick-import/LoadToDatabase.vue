<script setup lang="ts">
function append() {
  // TODO:
}

function merge() {
  // TODO:
}

function overwrite() {
  // TODO:
}
</script>

<template>
  <a-row :gutter="16">
    <a-col :span="8">
      <a-card :title="$t('activity.quickImport.loadToDataBase.append')" class="nc-import-action-button" @click="append">
        <p>{{ $t('activity.quickImport.loadToDataBase.appendDesc') }}</p>
      </a-card>
    </a-col>
    <a-col :span="8">
      <a-card :title="$t('activity.quickImport.loadToDataBase.merge')" class="nc-import-action-button" @click="merge">
        <p>{{ $t('activity.quickImport.loadToDataBase.mergeDesc') }}</p>
      </a-card>
    </a-col>
    <a-col :span="8">
      <a-card :title="$t('activity.quickImport.loadToDataBase.overwrite')" class="nc-import-action-button" @click="overwrite">
        <p>{{ $t('activity.quickImport.loadToDataBase.overwriteDesc') }}</p>
      </a-card>
    </a-col>
  </a-row>
</template>

<style lang="scss">
.nc-import-action-button {
  @apply shadow-md shadow-gray-400 ring-opacity-100 cursor-pointer;
}
</style>

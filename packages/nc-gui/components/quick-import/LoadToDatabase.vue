<script setup lang="ts">
function append() {
  // TODO:
  console.log('Append')
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
      <a-card :title="$t('activity.import.loadToDataBase.append')" :bordered="false" class="cursor-pointer" @click="append">
        <p>{{ $t('activity.import.loadToDataBase.appendDesc') }}</p>
      </a-card>
    </a-col>
    <a-col :span="8">
      <a-card :title="$t('activity.import.loadToDataBase.merge')" :bordered="false" class="cursor-pointer" @click="merge">
        <p>{{ $t('activity.import.loadToDataBase.mergeDesc') }}</p>
      </a-card>
    </a-col>
    <a-col :span="8">
      <a-card :title="$t('activity.import.loadToDataBase.overwrite')" :bordered="false" class="cursor-pointer" @click="overwrite">
        <p>{{ $t('activity.import.loadToDataBase.overwriteDesc') }}</p>
      </a-card>
    </a-col>
  </a-row>
</template>

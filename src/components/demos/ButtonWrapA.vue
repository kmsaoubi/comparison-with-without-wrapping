<template>
  <el-row class="mb-4">
    <PButton>Default</PButton>
    <PButton type="primary">Primary</PButton>
    <PButton type="success">Success</PButton>
    <PButton type="info">Info</PButton>
    <PButton type="warning">Warning</PButton>
    <PButton type="danger">Danger</PButton>
  </el-row>

  <el-row class="mb-4">
    <PButton plain>Plain</PButton>
    <PButton type="primary" plain>Primary</PButton>
    <PButton type="success" plain>Success</PButton>
    <PButton type="info" plain>Info</PButton>
    <PButton type="warning" plain>Warning</PButton>
    <PButton type="danger" plain>Danger</PButton>
  </el-row>

  <el-row class="mb-4">
    <PButton round>Round</PButton>
    <PButton type="primary" round>Primary</PButton>
    <PButton type="success" round>Success</PButton>
    <PButton type="info" round>Info</PButton>
    <PButton type="warning" round>Warning</PButton>
    <PButton type="danger" round>Danger</PButton>
  </el-row>

  <el-row>
    <PButton :icon="Search" circle />
    <PButton type="primary" :icon="Edit" circle />
    <PButton type="success" :icon="Check" circle />
    <PButton type="info" :icon="Message" circle />
    <PButton type="warning" :icon="Star" circle />
    <PButton type="danger" :icon="Delete" circle />
  </el-row>
</template>

<script lang="ts" setup>
import PButton from "../elements/PButton.vue"
import {
  Check,
  Delete,
  Edit,
  Message,
  Search,
  Star,
} from '@element-plus/icons-vue'
</script>
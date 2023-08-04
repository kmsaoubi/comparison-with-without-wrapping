<template>
  <PBreadcrumb :separator-icon="ArrowRight">
    <PBreadcrumbItem :to="{ path: '/' }">homepage</PBreadcrumbItem>
    <PBreadcrumbItem>promotion management</PBreadcrumbItem>
    <PBreadcrumbItem>promotion list</PBreadcrumbItem>
    <PBreadcrumbItem>promotion detail</PBreadcrumbItem>
  </PBreadcrumb>
</template>

<script lang="ts" setup>
import { ArrowRight } from '@element-plus/icons-vue'
import PBreadcrumb from "../elements/PBreadcrumb.vue"
import PBreadcrumbItem from "../elements/PBreadcrumbItem.vue"
</script>
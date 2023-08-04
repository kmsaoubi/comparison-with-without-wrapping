<template>
  <PBreadcrumb separator="/">
    <PBreadcrumbItem :to="{ path: '/' }">homepage</PBreadcrumbItem>
    <PBreadcrumbItem
      ><a href="/">promotion management</a></PBreadcrumbItem
    >
    <PBreadcrumbItem>promotion list</PBreadcrumbItem>
    <PBreadcrumbItem>promotion detail</PBreadcrumbItem>
  </PBreadcrumb>
</template>
<script setup>
import PBreadcrumb from "../elements/PBreadcrumb.vue"
import PBreadcrumbItem from "../elements/PBreadcrumbItem.vue"
</script>
<template>
  <div style="text-align: center">
    <el-row :gutter="200">
      <el-col :span="12"
        ><div class="grid-content ep-bg-purple" />
        <h1>NO WRAPPING</h1></el-col
      >
      <el-col :span="12"
        ><div class="grid-content ep-bg-purple-light" />
        <h1>WRAPPRING</h1></el-col
      >
    </el-row>
    <el-row :gutter="200">
      <el-col :span="24">
        <h2>ElAutocomplete</h2>
      </el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"
        >
        <AutocompleteA
      /></el-col>
      <el-col :span="12"
        >
        <AutocompleteWrapA
      /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"
        >
        <AutocompleteB
      /></el-col>
      <el-col :span="12"
        >
        <AutocompleteWrapB
      />
      <h5 style="color: red">Regression</h5></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><AutocompleteC
      /></el-col>
      <el-col :span="12"><AutocompleteWrapC
      /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="24">
        <h2>Avatar</h2>
      </el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><AvatarA /></el-col>
      <el-col :span="12"><AvatarWrapA /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><AvatarB /></el-col>
      <el-col :span="12"><AvatarWrapB /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><AvatarC/></el-col>
      <el-col :span="12"><AvatarWrapC /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><AvatarD /></el-col>
      <el-col :span="12"><AvatarWrapD /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="24">
        <h2>Breadcrumb</h2>
      </el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><BreadcrumbA /></el-col>
      <el-col :span="12"><BreadcrumbWrapA /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><BreadcrumbB /></el-col>
      <el-col :span="12"><BreadcrumbWrapB /></el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="24">
        <h2>Button</h2>
      </el-col>
    </el-row>
    <el-row :gutter="200">
      <el-col :span="12"><ButtonA/></el-col>
      <el-col :span="12"><ButtonWrapA />
      <h5 style="color: red">Regression</h5></el-col>
    </el-row>
  </div>
</template>
<script setup>
import AutocompleteA from "./demos/AutocompleteA.vue";
import AutocompleteB from "./demos/AutocompleteB.vue";
import AutocompleteC from "./demos/AutocompleteC.vue";
import AutocompleteWrapA from "./demos/AutocompleteWrapA.vue";
import AutocompleteWrapB from "./demos/AutocompleteWrapB.vue";
import AutocompleteWrapC from "./demos/AutocompleteWrapC.vue";
import AvatarA from "./demos/AvatarA.vue"
import AvatarWrapA from "./demos/AvatarWrapA.vue"
import AvatarB from "./demos/AvatarB.vue"
import AvatarWrapB from "./demos/AvatarWrapB.vue"
import AvatarC from "./demos/AvatarC.vue"
import AvatarWrapC from "./demos/AvatarWrapC.vue"
import AvatarD from "./demos/AvatarD.vue"
import AvatarWrapD from "./demos/AvatarWrapD.vue"
import BreadcrumbA from "./demos/BreadcrumbA.vue"
import BreadcrumbWrapA from "./demos/BreadcrumbWrapA.vue"
import BreadcrumbB from "./demos/BreadcrumbB.vue"
import BreadcrumbWrapB from "./demos/BreadcrumbWrapB.vue"
import ButtonA from "./demos/ButtonA.vue"
import ButtonWrapA from "./demos/ButtonWrapA.vue"
</script>

<style lang="scss">
.el-row {
  margin-bottom: 20px;
}
.el-row:last-child {
  margin-bottom: 0;
}
.el-col {
  border-radius: 4px;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
</style>

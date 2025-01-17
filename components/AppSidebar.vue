<script setup lang="ts">

</script>

<template>
  <Sidebar collapsible="icon" side="left" variant="sidebar">
    <SidebarHeader>
      EloDota
    </SidebarHeader>

    <SidebarContent>
      <SidebarGroup v-for="(item, index) in 5" :key="index">
        <SidebarGroupLabel>
          heading
        </SidebarGroupLabel>

        item
      </SidebarGroup>
    </SidebarContent>
  </Sidebar>
</template>

<style scoped>

</style>
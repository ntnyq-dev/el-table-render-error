<template>
  <main>
    <el-table :data="[1, 2, 3]">
      <el-table-column label="Foo">
        <template #default="{ $index }">
          {{ $index + 1 }}
        </template>
      </el-table-column>
      <el-table-column label="Bar">
        <template #default="{ $index }">
          {{ $index + 1 }}
        </template>
      </el-table-column>
    </el-table>

    <el-input placeholder="输入框可以正常渲染"></el-input>
  </main>
</template>

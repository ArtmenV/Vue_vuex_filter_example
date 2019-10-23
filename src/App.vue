<template>
  <div id="app">
    <el-containter>
      <el-header>Header here</el-header>
      <el-aside>amet consectetur adipisicing elit. Unde eligendi in voluptatem id, ad quia quam nisi eveniet</el-aside>
      <el-container>
        <el-main>main content here Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum vitae harum tempore expedita voluptas, architecto maiores itaque corporis repellendus iusto nesciunt ratione, provident optio quas perferendis delectus aliquid placeat deleniti.</el-main>
      </el-container>
    </el-containter>
    <router-view />
  </div>
</template>

<style>
.el-aside {
  background-color: chocolate;
  color: white;
  min-height: 100vh;
}
</style>

<template>
  <div class="container">
    <!-- 头部区域 -->
    <main-navbar></main-navbar>
    <!-- 导航菜单栏 -->
    <main-sidebar></main-sidebar>
    <!-- 主内容区域 -->
    <main-content></main-content>
  </div>
</template>

<script>
import MainNavbar from "./main/main-navbar";
import MainSidebar from "./main/main-sidebar";
import MainContent from "./main/main-content";

export default {
  name: "home",
  components: {
    MainNavbar,
    MainSidebar,
    MainContent
  }
};
</script>

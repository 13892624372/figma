<template>
  <section class="section-1">
    <!-- 背景图 -->
    <div class="hero-bg"></div>
    <!-- 遮罩层 -->
    <div class="hero-overlay"></div>
    
    <!-- 第1部分：Hero首页区域 -->
    <div class="hero-container">
      <!-- Logo -->
      <div class="logo">
        <img src="@/assets/logo.jpg" class="logo-img" alt="logo" />
      </div>
      
      <!-- 导航菜单 -->
      <nav class="nav-menu">
        <span @click="scrollToSection('section2')">公司简介</span>
        <span @click="scrollToSection('section2')">下属部门</span>
        <span @click="scrollToSection('section3')">解决方案</span>
        <span @click="scrollToSection('section4')">客户服务</span>
        <span @click="scrollToSection('section5')">可持续发展</span>
        <span @click="scrollToSection('section6')">联系我们</span>
      </nav>
      
      <!-- 主标题 -->
      <div class="hero-content">
        <h1 class="main-title">精诚品质 创造辉煌</h1>
        <p class="sub-title">Sincere quality, create resplendence</p>
        <p class="description">
          耀望立足于全球市场，始终致力成为拥有专业水平、具备响应力的可靠的钢材货源商，
          为客户提供优质、无瑕疵的材料产品
        </p>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
const scrollToSection = (sectionId: string) => {
  const element = document.getElementById(sectionId)
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' })
  }
}
</script>

<style scoped>
.section-1 {
  position: relative;
  width: 100%;
  height: 1000px;
  overflow: hidden;
}

.hero-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/1.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/2.jpg');
  background-size: cover;
  background-position: center;
  opacity: 0.7;
  z-index: 1;
}

.hero-container {
  position: relative;
  z-index: 2;
  width: 1920px;
  height: 100%;
  margin: 0 auto;
}

.logo {
  position: absolute;
  left: 42px;
  top: 30px;
  display: flex;
  align-items: center;
  gap: 20px;
  font-size: 48px;
  font-weight: bold;
  color: white;
}

.logo-img {
  width: 720px;
  height: 60px;
  object-fit: contain;
}

.nav-menu {
  position: absolute;
  right: 42px;
  top: 50px;
  display: flex;
  gap: 56px;
}

.nav-menu span {
  color: white;
  font-size: 28px;
  cursor: pointer;
  opacity: 0.9;
  transition: opacity 0.3s;
}

.nav-menu span:hover {
  opacity: 1;
}

.hero-content {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white;
}

.main-title {
  font-size: 96px;
  font-weight: bold;
  margin-bottom: 20px;
  letter-spacing: 8px;
}

.sub-title {
  font-size: 36px;
  opacity: 0.8;
  margin-bottom: 40px;
  letter-spacing: 2px;
}

.description {
  font-size: 32px;
  max-width: 800px;
  line-height: 1.8;
  opacity: 0.9;
  margin-top: 180px;
}
</style>

<template>
  <section id="section5" class="section-5">
    <!-- 第5部分：专业服务区域 -->
    <div class="service-container">
      <!-- 标题 -->
      <h2 class="section-title">专业服务</h2>
      <p class="section-subtitle">耀望始终致力于为每一位顾客提供最优质的全链服务</p>

      <!-- 三个服务卡片 -->
      <div class="service-cards">
        <!-- 卡片1 -->
        <div class="service-card card-1">
          <div class="card-inner">
            <!-- 背景图 -->
            <div class="card-bg"></div>
            <!-- 遮罩层 -->
            <div class="card-overlay"></div>
            <div class="card-content">
              <h3>专业咨询<br>与技术支持</h3>
              <div class="divider"></div>
              <div class="card-footer">
                <span>了解更多</span>
                <span class="arrow">→</span>
              </div>
            </div>
          </div>
        </div>

        <!-- 卡片2 -->
        <div class="service-card card-2">
          <div class="card-inner">
            <!-- 背景图 -->
            <div class="card-bg"></div>
            <!-- 遮罩层 -->
            <div class="card-overlay"></div>
            <div class="card-content">
              <h3>定制化<br>解决方案</h3>
              <div class="divider"></div>
              <div class="card-footer">
                <span>了解更多</span>
                <span class="arrow">→</span>
              </div>
            </div>
          </div>
        </div>

        <!-- 卡片3 -->
        <div class="service-card card-3">
          <div class="card-inner">
            <!-- 背景图 -->
            <div class="card-bg"></div>
            <!-- 遮罩层 -->
            <div class="card-overlay"></div>
            <div class="card-content">
              <h3>全链条<br>品质管控</h3>
              <div class="divider"></div>
              <div class="card-footer">
                <span>了解更多</span>
                <span class="arrow">→</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
.section-5 {
  position: relative;
  width: 100%;
  height: 1065px;
  background: #11365f;
  overflow: hidden;
}

.service-container {
  position: relative;
  width: 1920px;
  height: 1065px;
  margin: 0 auto;
  padding-top: 294px;
}

.section-title {
  text-align: center;
  font-size: 36px;
  font-weight: bold;
  color: white;
  margin-bottom: 11px;
}

.section-subtitle {
  text-align: center;
  font-size: 16px;
  color: rgba(255, 255, 255, 0.8);
  margin-bottom: 62px;
}

.service-cards {
  display: flex;
  justify-content: center;
  gap: 65px;
  padding: 0 358px;
}

.service-card {
  width: 354px;
  height: 424px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 4px;
  padding: 2px;
}

.card-inner {
  width: 350px;
  height: 420px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.15) 0%, rgba(255, 255, 255, 0.05) 100%);
  border-radius: 2px;
  position: relative;
  overflow: hidden;
}

/* 卡片1背景图 */
.card-1 .card-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/12.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

/* 卡片1遮罩层 */
.card-1 .card-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.75);
  z-index: 1;
}

.card-1 .card-content {
  position: relative;
  z-index: 2;
}

/* 卡片2背景图 */
.card-2 .card-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/13.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

/* 卡片2遮罩层 */
.card-2 .card-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.75);
  z-index: 1;
}

.card-2 .card-content {
  position: relative;
  z-index: 2;
}

/* 卡片3背景图 */
.card-3 .card-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/14.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

/* 卡片3遮罩层 */
.card-3 .card-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.75);
  z-index: 1;
}

.card-3 .card-content {
  position: relative;
  z-index: 2;
}

.card-content {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  padding: 30px;
  color: white;
}

.card-content h3 {
  font-size: 20px;
  font-weight: bold;
  line-height: 1.4;
  margin-bottom: 80px;
  min-height: 76px;
}

.divider {
  width: 100px;
  height: 1px;
  background: #e4e4e4;
  margin-bottom: 15px;
}

.card-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.card-footer span {
  font-size: 12px;
  opacity: 0.8;
}

.arrow {
  width: 28px;
  height: 28px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  transition: all 0.3s;
}

.arrow:hover {
  background: rgba(255, 255, 255, 0.4);
}
</style>

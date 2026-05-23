<template>
  <section id="section4" class="section-4">
    <!-- 背景图 -->
    <div class="section-bg"></div>
    
    <!-- 第4部分：应用领域区域 -->
    <div class="applications-container">
      <!-- 标题 -->
      <h2 class="section-title">广泛的应用领域</h2>
      
      <!-- 三个卡片 -->
      <div class="cards-container">
        <!-- 卡片1：航空航天 -->
        <div class="app-card card-1">
          <!-- 背景图 -->
          <div class="card-bg"></div>
          <!-- 遮罩层 -->
          <div class="card-overlay"></div>
          <div class="card-content">
            <h3>航空航天领域</h3>
            <p>耀望生产的优质不锈钢具有高温下的稳定性、较高的蠕变强度、良好的疲劳特性、缓慢的裂纹扩展等一系列优良属性，为航空航天领域优质首选。</p>
            <div class="card-footer">
              <span class="learn-more">了解更多</span>
              <span class="arrow">→</span>
            </div>
          </div>
        </div>
        
        <!-- 卡片2：重型运输 -->
        <div class="app-card card-2">
          <!-- 背景图 -->
          <div class="card-bg"></div>
          <!-- 遮罩层 -->
          <div class="card-overlay"></div>
          <div class="card-content">
            <h3>重型运输领域</h3>
            <p>高强度不锈钢在撞击时具有高能量吸收性，并且具有较高的防火性，可以广泛应用在薄壁罐式集装箱等运输领域。</p>
            <div class="card-footer">
              <span class="learn-more">了解更多</span>
              <span class="arrow">→</span>
            </div>
          </div>
        </div>

        <!-- 卡片3：汽车制造 -->
        <div class="app-card card-3">
          <!-- 背景图 -->
          <div class="card-bg"></div>
          <!-- 遮罩层 -->
          <div class="card-overlay"></div>
          <div class="card-content">
            <h3>汽车制造领域</h3>
            <p>创新不锈钢和高性能合金是改善可持续性、安全性和效率的重要驱动因素。已经在新能源汽车领域得到广泛应用。</p>
            <div class="card-footer">
              <span class="learn-more">了解更多</span>
              <span class="arrow">→</span>
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
.section-4 {
  position: relative;
  width: 100%;
  height: 800px;
  overflow: visible;
  z-index: 10;
}

/* 背景图 */
.section-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/8.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

.applications-container {
  position: relative;
  z-index: 1;
  position: relative;
  width: 1920px;
  height: 100%;
  margin: 0 auto;
  padding-top: 114px;
}

.section-title {
  text-align: center;
  font-size: 36px;
  font-weight: bold;
  color: white;
  margin-bottom: 85px;
}

.cards-container {
  display: flex;
  justify-content: center;
  gap: 60px;
  padding: 0 360px;
}

.app-card {
  width: 360px;
  height: 500px;
  background: linear-gradient(180deg, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0.05) 100%);
  border-radius: 8px;
  overflow: hidden;
  position: relative;
}

/* 卡片1背景图 */
.card-1 .card-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/9.jpg');
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
  background: rgba(0, 0, 0, 0.5);
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
  background-image: url('@/assets/10.jpg');
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
  background-image: url('@/assets/11.jpg');
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
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 14px;
}

.card-content p {
  font-size: 14px;
  line-height: 1.8;
  opacity: 0.9;
  margin-bottom: 60px;
}

.card-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 15px;
  border-top: 1px solid rgba(228, 228, 228, 0.3);
}

.learn-more {
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
  font-size: 14px;
  cursor: pointer;
  transition: all 0.3s;
}

.arrow:hover {
  background: rgba(255, 255, 255, 0.4);
}
</style>

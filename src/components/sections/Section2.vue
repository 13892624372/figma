<template>
  <section id="section2" class="section-2">
    <!-- 第2部分：品牌介绍区域 -->
    <div class="brand-container">
      <!-- 右侧背景图 -->
      <div class="right-bg"></div>
      <!-- 右侧遮罩 -->
      <div class="right-overlay"></div>
      
      <!-- 品牌文案 -->
      <div class="brand-text">
        <h2>品牌部分</h2>
        <p class="brand-subtitle">耀望实业集团有限公司，坐落于中国上海，拥有完整的钢铁生产工艺流程及相关配套设施。现已成为全国规模较大、工艺技术装备水平较高、品种规格较全的不锈钢企业。截止2010年年底，公司已通过经销 ，代销，现货直销方式与全球数多优秀钢厂达成合作伙伴关系，并常年备有质量优异的进口不锈钢、进口模具钢、进口高速钢。</p>
      </div>
      
      <!-- 中大图区域 -->
      <div class="main-image-area">
        <!-- 中大图背景 -->
        <div class="main-bg"></div>
        
        <!-- 下属部门标题 -->
        <div class="department-header">
          <h3>下属部门</h3>
          <p>耀望旗下子公司</p>
        </div>
        
        <!-- 滚动指示器 -->
        <div class="scroll-indicator"></div>
        
        <!-- 公司介绍卡片 -->
        <div class="company-card">
          <h4>上海耀望实业集团</h4>
          <p class="company-subtitle">不锈钢制品公司</p>
          <div class="divider"></div>
          <p class="company-desc">
            上海耀望不锈钢制品有限公司是一家销售各类特种不锈钢材料和纯钛钛合金材料的专业技术型公司。
            在近几年的发展中凭自身的努力拼搏和优质的服务及本着诚信的思想，获得国内外著名企业材料使用单位的好评，
            并获得了法国国际标准协会ISO9001的国际质量体系认证。
          </p>
          <button class="more-btn">更多 ></button>
        </div>
      </div>
      
      <!-- 左下角背景图 -->
      <div class="left-bg"></div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
.section-2 {
  position: relative;
  width: 100%;
  height: 1287px;
  background: #ffffff;
  overflow: hidden;
}

.brand-container {
  position: relative;
  width: 1921px;
  height: 1181px;
  margin: 0 auto;
}

/* 右侧背景图 */
.right-bg {
  position: absolute;
  left: 1220px;
  top: 0;
  width: 700px;
  height: 900px;
  background-image: url('@/assets/4.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

/* 右侧遮罩 */
.right-overlay {
  position: absolute;
  left: 1220px;
  top: 0;
  width: 700px;
  height: 900px;
  background-image: url('@/assets/3.jpg');
  background-size: cover;
  background-position: center;
  opacity: 0.7;
  z-index: 1;
}

/* 品牌文案 */
.brand-text {
  position: absolute;
  left: 360px;
  top: 110px;
  width: 688px;
}

.brand-text h2 {
  font-size: 48px;
  font-weight: bold;
  color: #1a1a1a;
  margin-bottom: 10px;
}

.brand-subtitle {
  font-size: 24px;
  color: #666;
  letter-spacing: 4px;
}

/* 中大图区域 */
.main-image-area {
  position: absolute;
  left: 360px;
  top: 500px;
  width: 1200px;
  height: 680px;
  z-index: 2;
}

/* 中大图背景 */
.main-bg {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-image: url('@/assets/5.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

/* 下属部门标题 */
.department-header {
  position: absolute;
  left: 796px;
  top: 110px;
  text-align: center;
}

.department-header h3 {
  font-size: 32px;
  font-weight: bold;
  color: #fff;
  margin-bottom: 10px;
}

.department-header p {
  font-size: 16px;
  color: rgba(255, 255, 255, 0.8);
}

/* 滚动指示器 */
.scroll-indicator {
  position: absolute;
  left: 51px;
  top: 406px;
  width: 4px;
  height: 188px;
  background: rgba(255, 255, 255, 0.5);
  border-radius: 2px;
}

/* 公司介绍卡片 */
.company-card {
  position: absolute;
  left: 600px;
  top: 320px;
  width: 600px;
  height: 360px;
  background: #041338;
  padding: 54px 74px;
  color: white;
}

.company-card h4 {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 6px;
}

.company-subtitle {
  font-size: 16px;
  opacity: 0.8;
  margin-bottom: 18px;
}

.divider {
  width: 450px;
  height: 1px;
  background: #fefefe;
  margin-bottom: 20px;
}

.company-desc {
  font-size: 14px;
  line-height: 1.8;
  opacity: 0.9;
  max-width: 447px;
}

.more-btn {
  position: absolute;
  left: 74px;
  bottom: 46px;
  background: transparent;
  border: 1px solid rgba(255, 255, 255, 0.5);
  color: white;
  padding: 8px 20px;
  cursor: pointer;
  font-size: 14px;
  transition: all 0.3s;
}

.more-btn:hover {
  background: rgba(255, 255, 255, 0.1);
  border-color: white;
}

/* 左下角背景图 */
.left-bg {
  position: absolute;
  left: 0;
  top: 780px;
  width: 600px;
  height: 400px;
  background-image: url('@/assets/6.jpg');
  background-size: cover;
  background-position: right center;
  z-index: 1;
}
</style>

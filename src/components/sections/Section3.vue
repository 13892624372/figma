<template>
  <section id="section3" class="section-3">
    <!-- 第3部分：公司实力区域 -->
    <div class="strength-container">
      <!-- 左侧背景图区域 -->
      <div class="left-bg-area">
        <!-- 背景图 -->
        <div class="bg-image"></div>
        <!-- 遮罩层 -->
        <div class="bg-overlay"></div>
        <!-- 渐变遮罩 -->
        <div class="mask-area">
          <div class="title-group">
            <h2 class="section-title">解决方案</h2>
            <p class="section-subtitle">丰富的应用场景</p>
          </div>
        </div>
      </div>
      
      <!-- 右侧内容区域 -->
      <div class="content-area">
        <h3 class="field-title">化工领域</h3>
        <p class="field-desc">
          我们提供极其广泛的不锈钢、高性能合金和专业服务，为您带来最佳的安全性能、产品性能和成本优化
        </p>
        <p class="field-detail">
          耀望生产的优质不锈钢以及高性能合金，包括钛、镍合金和锆等，可满足化学品行业的全部需求，包括低温应用、温度升高、高腐蚀性环境、高压处理等。以确保最终产品的高质量。
        </p>
        <button class="more-btn">更多 ></button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section-3 {
  position: relative;
  width: 100%;
  height: 605px;
  background: #f5f5f5;
  overflow: hidden;
}

.strength-container {
  position: relative;
  width: 1425px;
  height: 605px;
  margin: 0 auto;
  display: flex;
}

/* 左侧背景图区域 */
.left-bg-area {
  position: relative;
  width: 762px;
  height: 604px;
  overflow: hidden;
}

.bg-image {
  position: absolute;
  left: 0;
  top: 2px;
  width: 762px;
  height: 604px;
  background-image: url('@/assets/7.jpg');
  background-size: cover;
  background-position: center;
  z-index: 0;
}

.bg-overlay {
  position: absolute;
  left: 0;
  top: 2px;
  width: 762px;
  height: 604px;
  background: rgba(0, 0, 0, 0.5);
  z-index: 1;
}

.mask-area {
  position: absolute;
  left: 0;
  top: 0;
  width: 624px;
  height: 604px;
  background: linear-gradient(90deg, rgba(0,0,0,0.3) 0%, transparent 100%);
  display: flex;
  align-items: flex-start;
  justify-content: flex-end;
  padding-top: 0;
  z-index: 2;
}

.title-group {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  margin-top: 20px;
  margin-right: 20px;
}

.section-title {
  font-size: 64px;
  font-weight: bold;
  color: white;
  margin-bottom: 20px;
}

.section-subtitle {
  font-size: 28px;
  color: white;
  opacity: 0.8;
}

/* 右侧内容区域 */
.content-area {
  position: absolute;
  left: 769px;
  top: 262px;
  width: 655px;
  z-index: 3;
}

.field-title {
  font-size: 48px;
  font-weight: bold;
  color: #333;
  margin-bottom: 25px;
}

.field-desc {
  font-size: 26px;
  color: #666;
  line-height: 1.6;
  margin-bottom: 30px;
}

.field-detail {
  font-size: 24px;
  color: #666;
  line-height: 1.6;
  margin-bottom: 40px;
}

.more-btn {
  padding: 16px 36px;
  background: transparent;
  border: 1px solid #333;
  color: #333;
  cursor: pointer;
  font-size: 24px;
  transition: all 0.3s;
}

.more-btn:hover {
  background: #333;
  color: white;
}
</style>

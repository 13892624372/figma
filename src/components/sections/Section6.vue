<template>
  <section id="section6" class="section-6">
    <!-- 第6部分：页脚联系区域 -->
    <div class="footer-container">
      <!-- 联系信息块 -->
      <div class="contact-block">
        <h3>联系我们</h3>
        <div class="contact-info">
          <p>电话：021-57689316</p>
          <p>传真：021-57682993</p>
          <p>手机：13817101889</p>
          <p>联系人：林先生</p>
          <p>地址：上海市松江区泗泾镇泗砖路600号</p>
          <p>阿里巴巴：yaowang66.1688.com</p>
          <p>阿里旺旺：shyaowangsy</p>
        </div>
      </div>

      <!-- 导航链接 -->
      <nav class="footer-nav">
        <div class="nav-column">
          <h4>公司简介</h4>
          <ul>
            <li>关于我们</li>
            <li>发展历程</li>
            <li>企业文化</li>
          </ul>
        </div>
        <div class="nav-column">
          <h4>下属部门</h4>
          <ul>
            <li>不锈钢制品</li>
            <li>特种合金</li>
            <li>钛合金材料</li>
            <li>镍合金材料</li>
          </ul>
        </div>
        <div class="nav-column">
          <h4>解决方案</h4>
          <ul>
            <li>化工领域</li>
            <li>航空航天</li>
            <li>重型运输</li>
            <li>汽车制造</li>
          </ul>
        </div>
        <div class="nav-column">
          <h4>客户服务</h4>
          <ul>
            <li>售前咨询</li>
            <li>售后服务</li>
            <li>技术支持</li>
            <li>投诉建议</li>
          </ul>
        </div>
      </nav>

      <!-- 分隔线 -->
      <div class="divider"></div>

      <!-- 底部版权信息 -->
      <div class="copyright">
        <p>© 2024 上海耀望实业集团 版权所有 | 沪ICP备XXXXXXXX号</p>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
.section-6 {
  position: relative;
  width: 100%;
  height: 400px;
  background: #030d26;
  overflow: hidden;
}

.footer-container {
  position: relative;
  width: 1920px;
  height: 400px;
  margin: 0 auto;
  padding: 40px 360px;
  color: white;
}

/* 联系信息块 */
.contact-block {
  position: absolute;
  left: 1146px;
  top: 40px;
  width: 413px;
}

.contact-block h3 {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 20px;
}

.contact-info {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 10px 30px;
}

.contact-info p {
  font-size: 12px;
  opacity: 0.8;
  line-height: 1.6;
}

/* 导航链接 */
.footer-nav {
  position: absolute;
  left: 360px;
  top: 43px;
  display: flex;
  gap: 100px;
}

.nav-column h4 {
  font-size: 14px;
  font-weight: bold;
  margin-bottom: 15px;
  opacity: 0.9;
}

.nav-column ul {
  list-style: none;
  padding: 0;
}

.nav-column li {
  font-size: 12px;
  opacity: 0.7;
  line-height: 2;
  cursor: pointer;
  transition: opacity 0.3s;
}

.nav-column li:hover {
  opacity: 1;
}

/* 分隔线 */
.divider {
  position: absolute;
  left: 360px;
  top: 266px;
  width: 1200px;
  height: 1px;
  background: #d0d0d0;
  opacity: 0.5;
}

/* 版权信息 */
.copyright {
  position: absolute;
  left: 360px;
  top: 307px;
  width: 1200px;
  text-align: center;
}

.copyright p {
  font-size: 12px;
  opacity: 0.6;
}
</style>

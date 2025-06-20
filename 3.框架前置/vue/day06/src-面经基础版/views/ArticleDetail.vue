<template>
  <div class="article-detail-page">
    <nav class="nav"><span class="back">&lt;</span> 面经详情</nav>
    <header class="header">
      <h1>百度前端面经</h1>
      <p>2022-01-20 | 315 浏览量 | 44 点赞数</p>
      <p>
        <img
          src="http://teachoss.itheima.net/heimaQuestionMiniapp/%E5%AE%98%E6%96%B9%E9%BB%98%E8%AE%A4%E5%A4%B4%E5%83%8F%402x.png"
          alt=""
        />
        <span>青春少年</span>
      </p>
    </header>
    <main class="body">
      虽然百度这几年发展势头落后于AT, 甚至快被京东赶上了,毕竟瘦死的骆驼比马大,
      面试还是相当有难度和水准的, 一面.....
    </main>
  </div>
</template>

<script>
// 请求地址: https://mock.boxuegu.com/mock/3083/articles/:id
// 请求方式: get
export default {
  name: "ArticleDetailPage",
  data() {
    return {
      
    }
  }
}
</script>

<style lang="less" scoped>
.article-detail-page {
  .nav {
    height: 44px;
    border-bottom: 1px solid #e4e4e4;
    line-height: 44px;
    text-align: center;
    .back {
      font-size: 18px;
      color: #666;
      position: absolute;
      left: 10px;
      top: 0;
      transform: scale(1, 1.5);
    }
  }
  .header {
    padding: 0 15px;
    p {
      color: #999;
      font-size: 12px;
      display: flex;
      align-items: center;
    }
    img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      overflow: hidden;
    }
  }
  .body {
    padding: 0 15px;
  }
}
</style>
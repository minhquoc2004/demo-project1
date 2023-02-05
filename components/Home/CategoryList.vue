<template>
  <div class="category-list">
    <div class="container">
      <div class="list-category">
        <div class="title">
          <div class="title-name">Category list</div>
          <div class="button-view">
            <a href="https://kiante.wowtheme7.com/category/politics/">View All</a>
          </div>
        </div>
        <div class="menu">
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/business/">Business</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/marketing/">Marketing</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/motivation/">Motivation</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/politics/">Politics</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/sports/">Sports</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/technology/">Technology</a>
          </div>
          <div class="feature">
            <a href="https://kiante.wowtheme7.com/category/travel/">Travel</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.category-list {
  padding: 60px 0px;
}
@media (min-width: 1200px) {
  .container-xl, .container-lg, .container-md, .container-sm, .container {
    max-width: 1140px;
  }
}
.list-category {
  .title {
    display: flex;
    justify-content: space-between;
    .title-name {
      padding: 5px 10px;
      border-left: 4px solid red;
      color: #111111;
      font-family: "Roboto", Sans-serif;
      font-size: 24px!important;
      font-weight: 600;
      line-height: 32px!important;
      letter-spacing: -0.1px;
      position: relative;
    }
    .button-view {
      padding: 5px 0px;
      a {
        color: #111111;
        font-family: "Roboto", Sans-serif;
        font-size: 18px;
        font-weight: 600;
        text-decoration: none;
      }
    }
  }
  .menu {
    display: flex;
    padding: 20px 0px 0px;
    gap: 55px;
    .feature {
      a {
        color: #111;
        text-decoration: none;
        border-radius: 19px;
        background-color: white;
        box-shadow: 0px 0px 25px 0px rgb(208 208 208 / 22%);
        height: 39px;
        display: inline-block;
        line-height: 39px;
        width: 100%;
        text-align: center;
        padding: 0 20px;
      }
    }
    .feature:hover {
      a {
        color: red;
      }
    }
  }
}
</style>
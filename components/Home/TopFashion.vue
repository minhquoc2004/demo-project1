<template>
  <div class="top-fashion">
    <div class="container">
      <div class="fashion">
        <div class="title">
          <div class="title-name">Top Fashion</div>
          <div class="button-view">
            <a href="https://kiante.wowtheme7.com/category/politics/">View All</a>
          </div>
        </div>
        <div class="row">
          <div class="col-4">
            <div class="left-side-part">
              <div class="left-img">
                <div class="ratio">
                  <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/03/building-tall.jpg" alt="left-img" />
                </div>
              </div>
            </div>
          </div>
          <div class="col-8">
            <div class="right-side-part">
              <div class="right-img">
                <div class="ratio">
                  <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/03/nature.jpg" alt="right-img" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.top-fashion {
  background-color: #2D2D2D;
}
@media (min-width: 1200px) {
  .container-xl, .container-lg, .container-md, .container-sm, .container {
    max-width: 1140px;
  }
}
.fashion {
  padding: 60px 0px;
  .title {
    display: flex;
    justify-content: space-between;
    .title-name {
      padding: 5px 10px;
      border-left: 4px solid red;
      color: #FFFFFF;
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
        color: #FFFFFF;;
        font-family: "Roboto", Sans-serif;
        font-size: 18px;
        font-weight: 600;
        text-decoration: none;
      }
    }
  }
  .left-side-part {
    padding-top: 20px;
    .left-img {
      --bs-aspect-ratio: 126.42%;
    }
  }
  .right-side-part {
    padding-top: 20px;
    .right-img {
      --bs-aspect-ratio: 61.2%;
    }
  }
}
</style>
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
                  <div class="img-content">
                    <div class="category-box">
                      <a class="news-cat_Name" href="https://kiante.wowtheme7.com/category/technology/" style="background-color:#55cec0;">
                        Business</a>
                    </div>
                    <div class="post-title">
                      <a href="https://kiante.wowtheme7.com/lifestyle-carries-a-carry-in-peoples-life-can-you-ready/">Don’t be afraid to give up the good to go to for the great.</a>
                    </div>
                    <div class="post-author">
                      <img src="https://secure.gravatar.com/avatar/4baf8d27f33c75151b378befcd1ca61f?s=21&d=mm&r=g" alt="author" />
                      <a href="https://kiante.wowtheme7.com/author/admin/">Stiven Jackson</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-8">
            <div class="right-side-part">
              <div class="right-img">
                <div class="ratio">
                  <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/03/nature.jpg" alt="right-img" />
                  <div class="img-content">
                    <div class="category-box">
                      <a class="news-cat_Name" href="https://kiante.wowtheme7.com/category/technology/" style="background-color:#2aac37;">
                        Travel</a>
                    </div>
                    <div class="post-title">
                      <a href="https://kiante.wowtheme7.com/lifestyle-carries-a-carry-in-peoples-life-can-you-ready/">I find that the harder I work, the more luck I seem to have.</a>
                    </div>
                    <div class="post-author">
                      <div class="left">
                        <img src="https://secure.gravatar.com/avatar/4baf8d27f33c75151b378befcd1ca61f?s=21&d=mm&r=g" alt="author" />
                        <a href="https://kiante.wowtheme7.com/author/admin/">Stiven Jackson</a>
                      </div>
                      <div class="right">
                        <div class="clock-icon">
                          <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" color="white" viewBox="0 0 24 24"><path fill="white" d="M12 20c4.4 0 8-3.6 8-8s-3.6-8-8-8s-8 3.6-8 8s3.6 8 8 8m0-18c5.5 0 10 4.5 10 10s-4.5 10-10 10S2 17.5 2 12S6.5 2 12 2m.5 11H11l-4-2.3l.8-1.3l3.3 1.9V7h1.5v6Z"></path></svg>
                        </div>
                        <div class="time">Sep 25, 2022</div>
                      </div>
                    </div>
                  </div>
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
      img {
        border-radius: 5px;
      }
      .img-content {
        position: absolute;
        top: 62%;
        left: 10%;
        width: fit-content;
        block-size: fit-content;
        padding-right: 10px;
        a {
          text-decoration: none;
          color: white;
        }
        .category-box {
          a {
            padding: 5px 12px;
            border-radius: 5px;
            font-family: "Roboto", Sans-serif;
            font-size: 13px;
            font-weight: 400;
            line-height: 1em;
          }
        }
        .post-title {
          padding: 15px 0px 20px;
          font-family: "Lora", Sans-serif;
          font-size: 18px;
          font-weight: 600;
          line-height: 1.2em;
        }
        .post-author {
          display: flex;
          gap: 10px;
          img {
            border-radius: 50%;
          }
          a {
            font-family: "Roboto", Sans-serif;
            font-size: 14px;
            font-weight: 400;
            line-height: 20px;
          }
        }
      }
    }
  }
  .right-side-part {
    padding-top: 20px;
    .right-img {
      --bs-aspect-ratio: 61.2%;
      img {
        border-radius: 5px;
      }
      .img-content {
        position: absolute;
        top: 55%;
        left: 6%;
        width: fit-content;
        block-size: fit-content;
        a {
          text-decoration: none;
          color: white;
        }
        .category-box {
          a {
            padding: 5px 12px;
            border-radius: 5px;
            font-family: "Roboto", Sans-serif;
            font-size: 13px;
            font-weight: 400;
            line-height: 1em;
          }
        }
        .post-title {
          padding: 15px 0px;
          font-family: "Lora", Sans-serif;
          font-size: 32px;
          font-weight: 400;
          line-height: 36px;
        }
        .post-author {
          display: flex;
          gap: 30px;
          .left {
            display: flex;
            gap: 10px;
            img {
              border-radius: 50%;
            }
          }
          .right {
            display: flex;
            gap: 10px;
            .time {
              display: flex;
              align-items: center;
              color: white;
              font-family: "Roboto", Sans-serif;
              font-size: 14px;
              font-weight: 400;
              line-height: 20px;
            }
          }
        }
      }
    }
  }
}
</style>
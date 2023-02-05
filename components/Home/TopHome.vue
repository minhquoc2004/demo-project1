<template>
  <div class="top-home">
    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="left-side-bar">
            <div class="img1">
              <div class="ratio">
                <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/09/5.png" alt="img1" />
                <div class="img-content">
                  <div class="category-box">
                    <a class="news-cat_Name" href="https://kiante.wowtheme7.com/category/technology/" style="background-color:#f4af46;">
                      Technology</a>
                  </div>
                  <div class="post-title">
                    <a href="https://kiante.wowtheme7.com/everyone-has-the-right-to-be-happy-keep-the-smile-always/">Everyone has the right to be happy. <br/> Keep the smile always</a>
                  </div>
                  <div class="post-author">
                    <img src="https://secure.gravatar.com/avatar/4baf8d27f33c75151b378befcd1ca61f?s=21&d=mm&r=g" alt="author" />
                    <a href="https://kiante.wowtheme7.com/author/admin/">Stiven Jackson</a>
                  </div>
                </div>
              </div>
            </div>
            <div class="img2">
              <div class="ratio">
                <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/03/techboy.jpg" alt="img1" />
                <div class="img-content">
                  <div class="category-box">
                    <a class="news-cat_Name" href="https://kiante.wowtheme7.com/category/technology/" style="background-color:#f4af46;">
                      Technology</a>
                  </div>
                  <div class="post-title">
                    <a href="https://kiante.wowtheme7.com/intels-horseshoe-bend-concept-is-a-look-at-the-future-of-foldable/">Intel’s horseshoe bend concept is a <br />look at the future of foldable.</a>
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
          <div class="right-side-bar">
            <div class="img">
              <div class="ratio">
                <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/09/4.png" alt="img" />
                <div class="img-content">
                  <div class="category-box">
                    <a class="news-cat_Name" href="https://kiante.wowtheme7.com/category/technology/" style="background-color:#f4af46;">
                      Technology</a>
                  </div>
                  <div class="post-title">
                    <a href="https://kiante.wowtheme7.com/lifestyle-carries-a-carry-in-peoples-life-can-you-ready/">Lifestyle Carries a Carry in People’s Life. Can <br /> You Ready?</a>
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
</template>

<script>
export default {
  name: 'MdiClockTimeTenOutline'
}
</script>

<style lang="scss" scoped>
  @media (min-width: 1200px) {
    .container-xl, .container-lg, .container-md, .container-sm, .container {
      max-width: 1140px;
    }
  }
  .top-home {
    padding: 60px 0px;
    background: #F8F8F8;;
  }

  .left-side-bar {
    display: flex;
    flex-direction: column;
    gap: 20px;
    .img1, .img2  {
      --bs-aspect-ratio: 67.5%;
      position: relative;
      .img-content {
        position: absolute;
        top: 30%;
        left: 9%;
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
  .right-side-bar {
    .img {
      --bs-aspect-ratio: 68%;
      position: relative;
      .img-content {
        position: absolute;
        top: 61%;
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
</style>
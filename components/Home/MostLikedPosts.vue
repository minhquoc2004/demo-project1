<template>
  <div class="posts">
    <div class="container">
      <div class="most-liked-posts">
        <div class="title">
          <div class="title-name">Most Liked Posts</div>
          <div class="button-view">
            <a href="https://kiante.wowtheme7.com/category/politics/">View All</a>
          </div>
        </div>
        <div class="row">
          <div class="col-6">
            <div class="post">
              <div class="image">
                <a href="https://kiante.wowtheme7.com/here-are-ten-healthy-food-tips-that-you-follow-every-day/">
                  <div class="ratio">
                    <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/09/7.png" alt="post" />
                  </div>
                </a>
              </div>
              <div class="post-title">
                <a href="https://kiante.wowtheme7.com/here-are-ten-healthy-food-tips-that-you-follow-every-day/">Here are Ten Healthy Food Tips That You Follow Every Day</a>
              </div>
              <div class="post-author">
                <div class="left">
                  <img src="https://secure.gravatar.com/avatar/4baf8d27f33c75151b378befcd1ca61f?s=21&d=mm&r=g" alt="author" />
                  <a href="https://kiante.wowtheme7.com/author/admin/">Stiven Jackson</a>
                </div>
                <div class="right">
                  <div class="clock-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" color="#101010" viewBox="0 0 24 24"><path fill="currentColor" d="M12 20c4.4 0 8-3.6 8-8s-3.6-8-8-8s-8 3.6-8 8s3.6 8 8 8m0-18c5.5 0 10 4.5 10 10s-4.5 10-10 10S2 17.5 2 12S6.5 2 12 2m.5 11H11l-4-2.3l.8-1.3l3.3 1.9V7h1.5v6Z"></path></svg>
                  </div>
                  <div class="time">Sep 25, 2022</div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="post">
              <div class="image">
                <a href="https://kiante.wowtheme7.com/good-design-can-a-beautiful-raw-interface-for-everyone/">
                  <div class="ratio">
                    <img src="https://kiante.wowtheme7.com/wp-content/uploads/2022/09/6.png" alt="post" />
                  </div>
                </a>
              </div>
              <div class="post-title">
                <a href="https://kiante.wowtheme7.com/here-are-ten-healthy-food-tips-that-you-follow-every-day/">Good Design Can a Beautiful Raw Interface For Everyone</a>
              </div>
              <div class="post-author">
                <div class="left">
                  <img src="https://secure.gravatar.com/avatar/4baf8d27f33c75151b378befcd1ca61f?s=21&d=mm&r=g" alt="author" />
                  <a href="https://kiante.wowtheme7.com/author/admin/">Stiven Jackson</a>
                </div>
                <div class="right">
                  <div class="clock-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" color="#101010" viewBox="0 0 24 24"><path fill="currentColor" d="M12 20c4.4 0 8-3.6 8-8s-3.6-8-8-8s-8 3.6-8 8s3.6 8 8 8m0-18c5.5 0 10 4.5 10 10s-4.5 10-10 10S2 17.5 2 12S6.5 2 12 2m.5 11H11l-4-2.3l.8-1.3l3.3 1.9V7h1.5v6Z"></path></svg>
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
</template>

<style lang="scss" scoped>
.posts {
  padding: 60px 0px;
  background-color: #F8F8F8;
}
@media (min-width: 1200px) {
  .container-xl, .container-lg, .container-md, .container-sm, .container {
    max-width: 1140px;
  }
}
.most-liked-posts {
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
  .post {
    .image {
      padding: 20px 0px;
      --bs-aspect-ratio: 49.5%;
    }
    .post-title {
      a {
        font-family: "Lora", Sans-serif;
        font-size: 20px;
        font-weight: 400;
        line-height: 36px;
        letter-spacing: -0.01px;
        color: #111;
        text-decoration: none;
      }
    }
    .post-author {
      padding-top: 10px;
      display: flex;
      gap: 30px;
      .left {
        display: flex;
        gap: 10px;
        a {
          font-family: "Roboto", Sans-serif;
          letter-spacing: -0.01px;
          text-decoration: none;
          color:#111;
        }
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
          color: #111;
          font-family: "Roboto", Sans-serif;
          font-size: 14px;
          font-weight: 400;
          line-height: 20px;
        }
      }
    }
  }
}
</style>
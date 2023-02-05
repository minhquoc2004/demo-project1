<template>
  <div class="header">
    <div class="container">
      <div class="row">
        <div class="col-8">
          <div class="menu">
            <div class="feature nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="menu-deal" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Home
              </a>
            </div>
            <div class="feature">Business</div>
            <div class="feature">Politics</div>
            <div class="feature">Tech</div>
            <div class="feature nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="menu-deal" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Features
              </a>
            </div>
            <div class="feature">About</div>
            <div class="feature">Contact</div>
          </div>
        </div>
        <div class="col-4">
          <div class="search-icon">
            <Icon name="material-symbols:search" color="white" font-size="25px" />
            <!-- <IcOutlineYoutubeSearchedFor/> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  @media (min-width: 1200px) {
    .container-xl, .container-lg, .container-md, .container-sm, .container {
      max-width: 1140px;
    }
  }
  .header {
    color: white;
    padding: 20px 80px;
    background-color: transparent;
    background-image: linear-gradient(60deg, #5856D5 0%, #FF3A3A 100%);
  }
  .menu {
    display: flex;
    gap: 30px;
  }
  .search-icon {
    text-align: right;
  }
</style>
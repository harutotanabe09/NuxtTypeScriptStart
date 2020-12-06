<template>
  <!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8" />
      <meta
        name="viewport"
        content="width=device-width,initial-scale=1.0,user-scalable=no"
      />
      <meta property="og:type" content="website" />
      <meta property="og:title" content="なおと ポートフォリオ" />
      <meta property="og:url" content="URL入る" />
      <meta property="og:description" content="なおとのポートフォリオです。" />
      <meta property="og:image" content="img/ogp.png" />
      <meta name="description" content="なおとのポートフォリオです。" />
      <title>naoto portfolio</title>
      <link
        href="https://fonts.googleapis.com/css?family=Yesteryear"
        rel="stylesheet"
      />
      <link
        href="https://fonts.googleapis.com/css?family=Oswald:700"
        rel="stylesheet"
      />
      <link
        href="https://fonts.googleapis.com/css?family=Open+Sans:700"
        rel="stylesheet"
      />
      <link href="css/reset.css" media="all" rel="stylesheet" type="text/css" />
      <link
        href="css/photoswipe/photoswipe.css"
        media="all"
        rel="stylesheet"
        type="text/css"
      />
      <link
        href="css/photoswipe/default-skin/default-skin.css"
        media="all"
        rel="stylesheet"
        type="text/css"
      />
      <link href="css/style.css" media="all" rel="stylesheet" type="text/css" />
      <link
        rel="stylesheet"
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css"
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
        crossorigin="anonymous"
      />
      <link rel="shortcut icon" href="img/favicon2.ico" />
      <link
        rel="stylesheet"
        href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"
        integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO"
        crossorigin="anonymous"
      />
    </head>

    <body>
      <div id="wrapper">
        <header id="header">
          <h1 class="logo">
            <span class="logo-title">Naoto Suzuki's portfolio</span>
            <span class="logo-desc">Web Engineer</span>
          </h1>
        </header>
        <nav id="gnav">
          <ul>
            <li>
              <i class="fas fa-user fa-lg"><a href="#Profile">PROFILE</a></i>
            </li>
            <li>
              <i class="fas fa-lightbulb fa-lg"><a href="#skill">SKILL</a></i>
            </li>
            <li>
              <i class="fas fa-tasks fa-lg"><a href="#works">WORKS</a></i>
            </li>
            <li>
              <i class="fas fa-envelope fa-lg"
                ><a href="#contact">CONTACT</a></i
              >
            </li>
          </ul>
        </nav>
        <main id="contents">
          <section id="Profile" class="section">
            <div class="inner">
              <div class="section-title-block">
                <h2 class="section-title">
                  <i class="fas fa-user"
                    ><span class="section-title-css">PROFILE</span></i
                  >
                </h2>
              </div>
              <div class="two-column-wrapper">
                <div class="two-column-image profile">
                  <img src="img/profile/profile.JPG" alt="" />
                </div>
                <div class="two-column-desc">
                  <p class="text"></p>
                </div>
              </div>
            </div>
          </section>
          <section id="skill" class="section">
            <div class="inner">
              <div class="section-title-block">
                <h2 class="section-title">
                  <i class="fas fa-lightbulb fa-lg"
                    ><span class="section-title-css">SKILL</span></i
                  >
                </h2>
                <p class="section-desc"></p>
              </div>
              <div class="card-wrapper">
                <div class="card">
                  <div class="skill-desc">
                    <h3 class="skill-desc-title">
                      <i class="fas fa-desktop"></i>デザイン・コーディング
                    </h3>
                    <p>
                      基本的な事は一通りできます。CSSフレームワークはbootstrap使いました。
                    </p>
                    <table class="table table-borderless">
                      <CardItem class="name"></CardItem>
                      <tbody>
                        <tr>
                          <th scope="row">HTML5</th>
                          <td>1年</td>
                          <td>
                            <span class="rating"
                              ><p class="rate rate4"></p
                            ></span>
                          </td>
                        </tr>
                        <tr>
                          <th scope="row">CSS3</th>
                          <td>1年</td>
                          <td>
                            <span class="rating"
                              ><p class="rate rate4"></p
                            ></span>
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                </div>
                <div class="card">
                  <div class="skill-desc">
                    <h3 class="skill-desc-title">
                      <i class="fas fa-list-alt"></i>保有資格
                    </h3>
                    <p>社会人になってから取得したものです。</p>
                    <table class="table table-borderless">
                      <thead>
                        <tr>
                          <th scope="col">資格</th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr>
                          <th scope="row">基本情報技術者</th>
                        </tr>
                        <tr>
                          <th scope="row">Oracle Bronze</th>
                        </tr>
                        <tr>
                          <th scope="row">JavaSE8 silve</th>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                </div>
              </div>
            </div>
          </section>

          <section id="works" class="section">
            <div class="inner">
              <div class="section-title-block">
                <h2 class="section-title">
                  <i class="fas fa-tasks fa-lg"
                    ><span class="section-title-css">WORKS</span></i
                  >
                </h2>
                <div class="section-desc"></div>
              </div>
              <div class="card-wrapper my-gallery">
                <figure class="card">
                  <!-- <a href="img/works/dammy.jpg" data-size="980x668" class="card-image"> -->
                  <img
                    class="card-image"
                    src="img/works/thumb/portfolio.png"
                    alt=""
                  />
                  <!-- </a> -->
                  <figcaption class="card-caption">
                    <p class="card-caption-title">ポートフォリオ</p>
                    <p class="card-caption-info">
                      自分自身のポートフォリオです。
                    </p>
                    <p class="card-caption-info">HTML/CSS/bootstrap4</p>
                    <p class="card-caption-url">
                      <a
                        class="url-link"
                        href="https://github.com/spineSuzukiNaoto/portfolio"
                        target="_blank"
                        >git hub</a
                      >
                    </p>
                  </figcaption>
                </figure>
              </div>
            </div>
          </section>
        </main>
      </div>
    </body>
  </html>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  /*
  asyncData({}) {
    const skill = [{ name: '技術' }, { skill: '経験年数' }, { point: 'スキル' }]
    return {
      isLoading: false,
      skill: skill,
    }
  },
  */
})
</script>
<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>

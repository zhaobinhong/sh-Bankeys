<template>
  <div id="app">
    <header role="header" class="header-top" id="headere-top">

      <div class="header-fixed-wrapper" role="header-fixed">

        <div class="container">

          <!-- hgroup -->

          <hgroup class="row">

            <!-- logo -->

            <div class="col-xs-5 col-sm-2 col-md-2 col-lg-2">

              <h1>

                <a href="/" title="Bankeys"><img src="static/images/logo.png" alt="Bankeys" title="Bankeys"></a>

              </h1>

            </div>

            <!-- logo -->

            <!-- nav -->

            <nav role="navigation" class="col-xs-12 col-sm-10 col-md-10 col-lg-10 navbar navbar-default affix-top">

              <div id="navbar" class="navbar-collapse collapse">

                <ul class="nav navbar-nav">

                  <li class="active"><a href="#headere-top" title="Home">网站首页</a></li>

                  <li class=""><a href="#section-one" title="Overview">解决方案</a></li>

                  <li class=""><a href="#section-two" title="Features">新闻中心</a></li>

                  <li class=""><a href="#section-three" title="Pricing">下载中心</a></li>

                  <li class=""><a href="#section-four" title="Team">关于我们</a></li>
                  <li class="col-xs-3" style="color: #fff;cursor: pointer;text-align: center;">
                    <span class="glyphicon glyphicon-phone" aria-hidden="true"></span>
                    <span class="glyphicon-class">客户端</span>
                  </li>
                </ul>


              </div>

            </nav>

            <!-- nav -->

          </hgroup>

          <!-- hgroup -->

        </div>

      </div>

      <!-- banner Text -->

      <section class="text-center">

        <h2>eID</h2>

        <p>您的身份安全新标识</p>

      </section>


      <!-- banner image -->

      <figure>

        <div class="parallax-window item tp-banner-container" data-parallax="scroll" data-image-src="static/images/bg.jpg"
             style="height: 901px;"></div>

      </figure>

      <!-- banner image -->

    </header>

    <!-- content -->

    <router-view></router-view>



    <footer role="footer" class="footer text-center">

      <div class="container">

        <!-- socil-icons -->

        <section role="socil-icons" class="socil-icons">

          <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>

          <a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a>

          <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>

          <a href="#"><i class="fa fa-google-plus" aria-hidden="true"></i></a>

          <a href="#"><i class="fa fa-dribbble" aria-hidden="true"></i></a>

          <a href="#"><i class="fa fa-behance" aria-hidden="true"></i></a>

        </section>

        <!-- socil-icons -->

        <!-- nav -->

        <nav role="footer-nav">

          <a href="#">Terms of Use </a>

          <a href="#">Privacy Policy</a>

        </nav>

        <!-- nav -->

        <p class="copy">© 2017 Sartr. All rights reserved. More Templates <a href="http://www.cssmoban.com/" target="_blank" title="模板之家">1213</a> - Collect from <a href="http://www.cssmoban.com/" title="网页模板" target="_blank">模板</a></p>

      </div>

    </footer>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>

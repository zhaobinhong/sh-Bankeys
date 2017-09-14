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

                <a href="/" title="Bankeys"><img src="static/images/logoes/logo.png" alt="Bankeys" title="Bankeys"></a>

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

        <div class="parallax-window item tp-banner-container" id="homeBanner" data-parallax="scroll"
             style="background:#26283e;height: 901px;"></div>

      </figure>

      <!-- banner image -->

    </header>

    <!-- content -->

    <router-view></router-view>


    <footer role="footer" class="footer text-center">

      <div class="container">

        <div class="col-sm-8 col-md-8 col-lg-8">
          <p class="footer-default"></p>
          <div class="col-xs-4 col-sm-4 col-md-3 col-lg-3 contact-default">
            <h4>解决方案</h4>
            <p><a href="##">eISD／eID编码</a>
            </p>
            <p><a href="##">应用领域</a></p>
          </div>
          <div class="col-xs-4 col-sm-4 col-md-3 col-lg-3 contact-info">
            <h4>新闻中心</h4>
            <p><a href="##">新闻中心</a>
            </p>
          </div>
          <div class="col-xs-4 col-sm-4 col-md-3 col-lg-3 contact-info">
            <h4>下载中心</h4>
            <p><a href="##">下载中心</a>
            </p>
          </div>

          <div class="col-xs-4 col-sm-4 col-md-3 col-lg-3 contact-info">
            <h4>关于我们</h4>
            <p><a href="##">公司概况</a>
            </p>
            <p><a href="##">联系我们</a>
            </p>
          </div>
        </div>
        <div class="col-sm-4 col-md-4 col-lg-4 ">
          <p class="footer-default"></p>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 contact-default">
            <h4><a class="opinion" href="##"><span class="pen"></span>意见反馈</a></h4>
          </div>

        </div>

      </div>
      <div class="col-sm-12 col-md-12 col-lg-12 endFooter">
        <div class="col-xs-8 col-sm-8 col-md-8 col-lg-8 contact-default">
          <p>沪 CP 备14034910号－1｜上海市愚园路1107号6号楼5-6层</p>
        </div>
        <div class="col-xs-4 col-sm-4 col-md-4 col-lg-4 contact-default">
          <p><a href="##"><span class="contact"></span>联系我们</a></p>
        </div>

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

  footer {
    color: rgba(255, 255, 255, .5);
  }

  footer h4 {
    color: #fff;
    font-weight: bold;
  }

  footer a, footer a:link {
    color: rgba(255, 255, 255, .5);
    text-decoration: none;
  }

  footer a:hover, footer a:visited, footer a:active {
    color: #fff;
    text-decoration: none;
  }

  .pen {
    display: inline-block;
    width: 17px;
    height: 17px;
    background-image: url('/static/images/index/feedback.png');
    background-repeat: no-repeat;
    position: relative;
    left: -10px;
    top: 2px;
  }

  footer a.opinion {
    color: #fff;
  }

  .endFooter{
    background: #2f3949;
    padding-top: 30px;
    height: 80px;
    line-height: 1;
    color: #fff;
  }

  .endFooter p{
    height: 20px;
    line-height: 1;
  }

  .endFooter p a{
    position: relative;
    top: -4px;
  }

  .contact{
    display: inline-block;
    width: 19px;
    height: 20px;
    background-image: url('/static/images/index/contact.png');
    background-repeat: no-repeat;
    position: relative;
    left: -10px;
    top: 2px;
  }

</style>

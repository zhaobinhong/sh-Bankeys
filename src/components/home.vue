<template>
  <div class="main">
    <div class="wrapper" style="overflow: hidden">
      <div class="li col-md-10 col-md-offset-1">
        <div class="col-md-6 text-left">
          <h4>高安全的身份电子标识</h4>
          <p>由“公安部公民网络身份识别系统”签发给公民的网络电子身份标识，能够在不泄露身份信息的前提下在线远程识别身份。</p>
        </div>
        <div class="col-md-6 text-right"><img src="static/images/home/identity.png" alt="高安全身份电子标识"></div>
      </div>
      <div class="li col-md-10 col-md-offset-1">

        <div class="col-md-6 text-left"><img src="static/images/home/verification.png" alt="多元素支撑便于跨域验证"></div>
        <div class="col-md-6 text-right">
          <h4>多元素支撑便于跨域验证</h4>
          <p>支持多接口、多行业、多渠道、多场景、的一体化服务，区别于普通密码、图文认证方式，多元技术支撑高级加密口令线上核验。</p>
        </div>
      </div>
      <div class="li col-md-10 col-md-offset-1">
        <div class="col-md-6 text-left">
          <h4>强大的数据云计算能力</h4>
          <p>基于云计算、活体检测、人证对比、图像特征识别等技术，向海量认证信息快速处理响应。</p>
        </div>
        <div class="col-md-6 text-right"><img src="static/images/home/cloud-computing.png" alt="强大的数据云计算能力"></div>
      </div>
      <div class="li end col-md-10 col-md-offset-1">

        <div class="col-md-6 text-left"><img src="static/images/home/electronic-signature.png" alt="多场景电子签名支持"></div>
        <div class="col-md-6 text-right">
          <h4>多场景电子签名支持</h4>
          <p>eID编码持有人可在多类线上实名制信息加密过程使用，并明确网络行为出于公民本人意愿。</p>
        </div>
      </div>

      <hr class="col-md-12"/>

      <div class="advantage col-md-12">
        <div class="hed">
          <h3>以eID为中心的产品优势</h3>
          <p>公共安全领域的管控卫士</p>
        </div>

        <ul class="advList text-center">
          <li>
            <img src="static/images/home/fast.png" alt="快捷">
            <h4>办理更快捷</h4>
            <p>所有流程在线完成</p>
            <p>过程数字化</p>
            <p>节省线下办理时间</p>
          </li>
          <li>
            <img src="static/images/home/safe.png" alt="安全">
            <h4>过程更安全</h4>
            <p>采用国家级加密算法</p>
            <p>客户隐私信息三重加密</p>
            <p>专利技术确保安全</p>
          </li>
          <li>
            <img src="static/images/home/cost.png" alt="低成本">
            <h4>可靠成本低</h4>
            <p>产品无需附加硬件</p>
            <p>依托高效智能软件</p>
            <p>最大化降低客户成本</p>
          </li>
          <li>
            <img src="static/images/home/features.png" alt="功能全">
            <h4>功能更全面</h4>
            <p>加入人脸识别技术</p>
            <p>实现线上实人验证</p>
            <p>业务数字签名</p>
          </li>
        </ul>

      </div>

      <hr class="col-md-12"/>

      <div class="partner col-md-12">

        <div class="hed">
          <h3>他们选择了上海收付宝</h3>
          <p>值得心来的合作伙伴</p>
        </div>

        <ul class="partnerQY">
          <li class="col-md-3"><img src="static/images/home/public-security.png" alt="公安三所"></li>
          <li class="col-md-3"><img src="static/images/home/airport.png" alt="上海机场"></li>
          <li class="col-md-3"><img src="static/images/home/hong-yi.png" alt="红翌科技"></li>
          <li class="col-md-3"><img src="static/images/home/da-hua.png" alt="dahua"></li>

        </ul>

        <ul class="partnerQY">
          <li class="col-md-3"><img src="static/images/home/tsinghua.png" alt="清华大学"></li>
          <li class="col-md-3"><img src="static/images/home/wuhan.png" alt="武汉大学"></li>
          <li class="col-md-3"><img src="static/images/home/siant.png" alt="上海网络技术研究所"></li>
          <li class="col-md-3"><img src="static/images/home/bankeys.png" alt="收付宝"></li>
        </ul>

      </div>
    </div>


  </div>
</template>

<script>
  export default {
    name: 'main',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  body{
    overflow-x: -webkit-paged-y;
  }

  hr {
    color: #bbb;
  }

  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }

  div.li {
    padding-top: 84px;
    padding-bottom: 84px;
    border-bottom: 1px solid #bbb;
  }

  .li img {
    display: inline-block;
    display: -webkit-inline-box;
  }

  .li h4 {
    color: #5895f1;
    font-size: 24px;
    line-height: 1;
    margin-top: 48px;
  }

  .li p {
    font-size: 18px;
    line-height: 26px;
  }

  div.end {
    border-bottom: none;
  }

  .hed{
    margin-top: 5rem;
  }

  .hed h3{
    font-size: 24px;
    color: #000;
  }

  .hed p{
    font-size: 18px;
    color: #aaa;
  }

  .advList {
    overflow: hidden;
    display: inline-block;
    margin: 0 auto;
  }

  .advList li {
    margin: 2em 2em;
    cursor: pointer;
    border-radius: 8px;
    float: left;
    width: 200px;
    height: 260px;
    background: #f2f2f2;
    transition: all .6s;
  }

  .advList li:hover {
    transform: scale(1.1);
    box-shadow: 0px 5px 8.6px 1.4px rgba(67, 67, 67, 0.3);
  }

  .advList li img {
    padding: 22px 0;
    display: inline-block;
    margin: 0 auto;
  }

  .advList li h4{
    font-size: 20px;
    font-weight: 600;
  }

  .advList li p{
    font-size: 16px;
    line-height: 20px;
  }

  .partnerQY{
    overflow: hidden;
  }
  .partnerQY li{
    margin: 20px 0px;
    padding: 26px 0;
  }

  .partnerQY li:hover{
    cursor: pointer;
    box-shadow: 5px 5px 8px rgba(67, 67, 67, 0.3) inset,-5px -5px 8px rgba(67, 67, 67, 0.3) inset;
  }

  .partnerQY li img{
    display: inline-block;
    margin: 0 auto;
  }

</style>

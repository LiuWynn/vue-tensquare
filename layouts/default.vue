<template>
  <div>
    <!--引用组件-->
    <div class="activity-head">
      <div class="wrapper">
        <!--头部导航-->
        <header>
          <div class="sui-navbar">
            <div class="navbar-inner">
              <a href="index-logined.html" class="sui-brand">
                <img src="~/assets/img/asset-logo-black.png" alt="社交" />
              </a>
              <ul class="sui-nav">
                <!-- <li class="active">
                  <a href="/">头条</a>
                </li>
                <li>
                  <a href="/qa">问答</a>
                </li>
                <li>
                  <a href="/gathering">活动</a>
                </li>
                <li>
                  <a href="/friend">交友</a>
                </li>
                <li>
                  <a href="/spit">吐槽</a>
                </li>
                <li>
                  <a href="/recruit">招聘</a>
                </li>-->
                <router-link tag="li" to="/" active-class="active" exact>
                  <a>头条</a>
                </router-link>
                <router-link tag="li" to="/qa" active-class="active">
                  <a>问答</a>
                </router-link>
                <router-link tag="li" to="/gathering" active-class="active">
                  <a>活动</a>
                </router-link>
                <router-link tag="li" to="/friend" active-class="active">
                  <a>交友</a>
                </router-link>
                <router-link tag="li" to="/spit" active-class="active">
                  <a>吐槽</a>
                </router-link>
                <router-link tag="li" to="/recruit" active-class="active">
                  <a>招聘</a>
                </router-link>
              </ul>
              <form class="sui-form sui-form pull-left">
                <input type="text" placeholder="输入关键词..." />
                <!-- <span class="btn-search fa fa-search"></span> -->
              </form>
              <div class="sui-nav pull-right info">
                <li>
                  <a href="~/assets/other-notice.html" target="_blank" class="notice">小强</a>
                </li>
                <li>
                  <a href="~/assets/person-homepage.html" target="_blank" class="homego">
                    <img src="~/assets/img/widget-photo.png" alt="用户头像" />
                  </a>
                </li>
              </div>
            </div>
          </div>
        </header>
      </div>
    </div>
    <nuxt />
    <footer>
      <div class="footer">
        <div class="wrapper">
          <div class="footer-bottom">
            <div class="link">
              <dl>
                <dt>网站相关</dt>
                <dd>关于我们</dd>
                <dd>服务条款</dd>
                <dd>帮助中心</dd>
                <dd>编辑器语法</dd>
              </dl>
              <dl>
                <dt>常用链接</dt>
                <dd>传智播客</dd>
                <dd>传智论坛</dd>
              </dl>
              <dl>
                <dt>联系我们</dt>
                <dd>联系我们</dd>
                <dd>加入我们</dd>
                <dd>建议反馈</dd>
              </dl>
              <dl>
                <dt>关注我们</dt>
                <dd>微博</dd>
                <dd>twitter</dd>
              </dl>
              <div class="xuke">
                <h3>内容许可</h3>
                <p>除特别说明外，用户内容均采用知识共享署名-非商业性使用-禁止演绎4.0 国际许可协议 (CC BY-NC-ND 4.0) 进行许可</p>
                <p>本站由 传智研究院 提供更新服务</p>
              </div>
            </div>
            <p class="Copyright">Copyright &copy; 2017 传智问答社区 当前版本 0.0.1</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import '~/assets/plugins/normalize-css/normalize.css'
import '~/assets/plugins/yui/cssgrids-min.css'
import '~/assets/plugins/sui/sui.min.css'
import '~/assets/plugins/sui/sui-append.min.css'
import '~/assets/plugins/font-awesome/css/font-awesome.min.css'
import '~/assets/css/widget-base.css'
import '~/assets/css/widget-head-foot.css'
export default {

}
</script>
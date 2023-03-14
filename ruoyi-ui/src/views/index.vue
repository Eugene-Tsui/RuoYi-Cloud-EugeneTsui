<template>
  <div class="app-container home">
    <el-row :gutter="20">
      <el-col :sm="24" :lg="24">
        <blockquote class="text-warning" style="font-size: 14px">
          微服务后台管理系统
          微服务后台管理系统
          微服务后台管理系统
        </blockquote>

        <hr />
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :sm="24" :lg="12" style="padding-left: 20px">
        <h2>EugeneTsui后台管理框架</h2>
<!--        <p>-->
<!--          一直想做一款后台管理系统，看了很多优秀的开源项目但是发现没有合适自己的。于是利用空闲休息时间开始自己写一套后台系统。如此有了若依管理系统，她可以用于所有的Web应用程序，如网站管理后台，网站会员中心，CMS，CRM，OA等等，当然，您也可以对她进行深度定制，以做出更强系统。所有前端后台代码封装过后十分精简易上手，出错概率低。同时支持移动客户端访问。系统会陆续更新一些实用功能。-->
<!--        </p>-->
        <p>
          <b>当前版本:</b> <span>v{{ version }}</span>
        </p>
        <p>
          <el-tag type="danger">&yen;练手系统</el-tag>
        </p>
<!--        <p>-->
<!--          <el-button-->
<!--            type="primary"-->
<!--            size="mini"-->
<!--            icon="el-icon-cloudy"-->
<!--            plain-->
<!--            @click="goTarget('https://gitee.com/y_project/RuoYi-Cloud')"-->
<!--            >访问码云</el-button-->
<!--          >-->
<!--          <el-button-->
<!--            size="mini"-->
<!--            icon="el-icon-s-home"-->
<!--            plain-->
<!--            @click="goTarget('http://ruoyi.vip')"-->
<!--            >访问主页</el-button-->
<!--          >-->
<!--        </p>-->
      </el-col>

      <el-col :sm="24" :lg="12" style="padding-left: 50px">
        <el-row>
          <el-col :span="12">
            <h2>技术选型</h2>
          </el-col>
        </el-row>
        <el-row>
          <el-col :span="6">
            <h4>后端技术</h4>
            <ul>
              <li>SpringBoot</li>
              <li>SpringCloud</li>
              <li>Nacos</li>
              <li>Sentinel</li>
              <li>Seata</li>
              <li>Minio</li>
              <li>...</li>
            </ul>
          </el-col>
          <el-col :span="6">
            <h4>前端技术</h4>
            <ul>
              <li>Vue</li>
              <li>Vuex</li>
              <li>Element-ui</li>
              <li>Axios</li>
              <li>Echarts</li>
              <li>Quill</li>
              <li>...</li>
            </ul>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
    <el-divider />
    <el-row :gutter="20">
<!--      <el-col :xs="24" :sm="24" :md="12" :lg="8">-->
<!--        <el-card class="update-log">-->
<!--          <div slot="header" class="clearfix">-->
<!--            <span>联系信息</span>-->
<!--          </div>-->
<!--          <div class="body">-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="el-icon-s-promotion"></i> 官网：<el-link&ndash;&gt;-->
<!--&lt;!&ndash;                href="http://www.ruoyi.vip"&ndash;&gt;-->
<!--&lt;!&ndash;                target="_blank"&ndash;&gt;-->
<!--&lt;!&ndash;                >http://www.ruoyi.vip</el-link&ndash;&gt;-->
<!--&lt;!&ndash;              >&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="el-icon-user-solid"></i> QQ群：<s>满42799195</s> <s>满170157040</s>&ndash;&gt;-->
<!--&lt;!&ndash;              <s>满130643120</s> <s>满225920371</s> <s>满201705537</s> <s>满236543183</s>&ndash;&gt;-->
<!--&lt;!&ndash;              <s>满213618602</s> <s>148794840</s> <a href="https://jq.qq.com/?_wv=1027&k=MtBy6YfT" target="_blank">&ndash;&gt;-->
<!--&lt;!&ndash;                118752664</a&ndash;&gt;-->
<!--&lt;!&ndash;              >&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="el-icon-chat-dot-round"></i> 微信：<a&ndash;&gt;-->
<!--&lt;!&ndash;                href="javascript:;"&ndash;&gt;-->
<!--&lt;!&ndash;                >/ *若依</a&ndash;&gt;-->
<!--&lt;!&ndash;              >&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="el-icon-money"></i> 支付宝：<a&ndash;&gt;-->
<!--&lt;!&ndash;                href="javascript:;"&ndash;&gt;-->
<!--&lt;!&ndash;                class="支付宝信息"&ndash;&gt;-->
<!--&lt;!&ndash;                >/ *若依</a&ndash;&gt;-->
<!--&lt;!&ndash;              >&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--          </div>-->
<!--        </el-card>-->
<!--      </el-col>-->
<!--      <el-col :xs="24" :sm="24" :md="12" :lg="8">-->
<!--        <el-card class="update-log">-->
<!--          <div slot="header" class="clearfix">-->
<!--            <span>更新日志</span>-->
<!--          </div>-->
<!--&lt;!&ndash;          <el-collapse accordion>&ndash;&gt;-->
<!--&lt;!&ndash;            <el-collapse-item title="v3.6.2 - 2023-01-16">&ndash;&gt;-->
<!--&lt;!&ndash;              <ol>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>重置时取消部门选中</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>升级pagehelper到最新版1.4.6</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>升级transmittable-thread-local到最新版本2.14.2</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>升级echarts到最新版本5.4.0</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>升级core-js到最新版本3.25.3</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>优化字符未使用下划线不进行驼峰式处理</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>优化nacos修改xss开关时同步过滤器验证</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>优化修改头像在小屏幕上页面布局错位的问题</li>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>其他细节优化</li>&ndash;&gt;-->
<!--&lt;!&ndash;              </ol>&ndash;&gt;-->
<!--&lt;!&ndash;            </el-collapse-item>&ndash;&gt;-->

<!--&lt;!&ndash;            <el-collapse-item title="v1.0.0 - 2020-05-20">&ndash;&gt;-->
<!--&lt;!&ndash;              <ol>&ndash;&gt;-->
<!--&lt;!&ndash;                <li>若依微服务系统正式发布</li>&ndash;&gt;-->
<!--&lt;!&ndash;              </ol>&ndash;&gt;-->
<!--&lt;!&ndash;            </el-collapse-item>&ndash;&gt;-->
<!--&lt;!&ndash;          </el-collapse>&ndash;&gt;-->
<!--        </el-card>-->
<!--      </el-col>-->
<!--      <el-col :xs="24" :sm="24" :md="12" :lg="8">-->
<!--        <el-card class="update-log">-->
<!--          <div slot="header" class="clearfix">-->
<!--            <span>捐赠支持</span>-->
<!--          </div>-->
<!--&lt;!&ndash;          <div class="body">&ndash;&gt;-->
<!--&lt;!&ndash;            <img&ndash;&gt;-->
<!--&lt;!&ndash;              src="https://oscimg.oschina.net/oscnet/up-d6695f82666e5018f715c41cb7ee60d3b73.png"&ndash;&gt;-->
<!--&lt;!&ndash;              alt="donate"&ndash;&gt;-->
<!--&lt;!&ndash;              width="100%"&ndash;&gt;-->
<!--&lt;!&ndash;            />&ndash;&gt;-->
<!--&lt;!&ndash;            <span style="display: inline-block; height: 30px; line-height: 30px"&ndash;&gt;-->
<!--&lt;!&ndash;              >你可以请作者喝杯咖啡表示鼓励</span&ndash;&gt;-->
<!--&lt;!&ndash;            >&ndash;&gt;-->
<!--&lt;!&ndash;          </div>&ndash;&gt;-->
<!--        </el-card>-->
<!--      </el-col>-->
    </el-row>
  </div>
</template>

<script>
export default {
  name: "Index",
  data() {
    return {
      // 版本号
      version: "0.0.1",
    };
  },
  methods: {
    goTarget(href) {
      window.open(href, "_blank");
    },
  },
};
</script>

<style scoped lang="scss">
.home {
  blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee;
  }
  hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee;
  }
  .col-item {
    margin-bottom: 20px;
  }

  ul {
    padding: 0;
    margin: 0;
  }

  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    list-style-type: none;
  }

  h4 {
    margin-top: 0px;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  p {
    margin-top: 10px;

    b {
      font-weight: 700;
    }
  }

  .update-log {
    ol {
      display: block;
      list-style-type: decimal;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0;
      margin-inline-end: 0;
      padding-inline-start: 40px;
    }
  }
}
</style>


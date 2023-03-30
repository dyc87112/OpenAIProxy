
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、服务名、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# openai-proxy 帮助文档

<p align="center" class="flex justify-center">
    <a href="https://www.serverless-devs.com" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=openai-proxy&type=packageType">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=openai-proxy" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=openai-proxy&type=packageVersion">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=openai-proxy" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=openai-proxy&type=packageDownload">
  </a>
</p>

<description>

一键部署OpenAI的代理，以方便实现OpenAI的API调用。

</description>

## 前期准备

使用该项目，您需要有开通以下服务：

- 函数计算 FC

推荐您拥有以下的产品权限 / 策略：

- 函数计算 / AliyunFCFullAccess

## 应用中心一键部署

通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=openai-proxy) ，点击下面按钮直接部署体验：

[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=openai-proxy)

## Serverless Devs Cli 部署

1. [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://docs.serverless-devs.com/fc/config) ； 
2. 初始化项目：`s init openai-proxy -d openai-proxy `
3. 进入项目，并进行项目部署：`cd openai-proxy && s deploy - y`

## 使用文档

<usedetail id="flushContent">

部署完成之后，获得一个域名，该域名可以用来替代 https://api.openai.com 来使用。

</usedetail>

## 深入交流

欢迎关注公众号：程序猿DD，分享前沿技术资讯，一起探索ChatGPT



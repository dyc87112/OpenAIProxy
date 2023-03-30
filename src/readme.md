
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

<service>

| 服务 |  备注  |
| --- |  --- |
| 函数计算 FC |  快速体验部署openai-proxy |

</service>

推荐您拥有以下的产品权限 / 策略：

<auth>

| 服务/业务 |  权限 |  备注  |
| --- |  --- |   --- |
| 函数计算 | AliyunFCFullAccess |  快速体验部署openai-proxy |

</auth>

## 部署 & 体验

<appcenter>
   
- 通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=openai-proxy) ，
  [![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=openai-proxy) 该应用。
   
</appcenter>

<deploy>
    
- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
  - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://docs.serverless-devs.com/fc/config) ；
  - 初始化项目：`s init openai-proxy -d openai-proxy `
  - 进入项目，并进行项目部署：`cd openai-proxy && s deploy - y`
   
</deploy>

## 应用详情

<appdetail id="flushContent">
</appdetail>

## 使用文档

<usedetail id="flushContent">

部署完成之后，获得一个域名，该域名可以用来替代 https://api.openai.com 来使用。

</usedetail>

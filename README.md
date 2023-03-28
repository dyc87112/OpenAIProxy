# 项目说明

实现阿里云函数计算一键部署OpenAI的代理，以方便实用OpenAI API的调用。

# 使用说明

1. 通过阿里云函数计算部署
2. 绑定自定义域名，比如：http://openai-proxy.abc123.com
3. 在后续需要调用 https://api.openapi.com 的地方使用上面自定义的域名

# 实现原理

本项目根据 https://github.com/Ice-Hazymoon/openai-scf-proxy/ 的实现，配置成可以一键部署的方式

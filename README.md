# Dipbit Pay Gateway API 
## 商户接入
### 概述
商户接入Dipbit支付系统能够完成的功能包括充币、提币、充币查询、提币查询、余额查询。客服人员在完成商户的注册之后，会将一次性激活密钥颁发给商户，
一次性激活密钥有效期为24小时，用户在获取激活密钥后，需要尽快调用激活授权API，完成激活并获取调用支付API接口所需要的ACCESS_KEY和ACCESS_SECRET。
## 激活授权API
环境 | HTTPS请求地址
------------ | -------------
正式环境 | https://paygw.dipbit.com/key/init

请求参数

参数名称 | 参数说明
------------ | -------------
正式环境 | https://paygw.dipbit.com/key/init

## 支付API
API 详见 https://app.swaggerhub.com/apis/HollyAtGwave/dipbit-pay_gateway_api/1.0.0
1. **充币申请**

2. **充币查询**

3. **提币申请**

4. **提币查询**

5. **余额查询**

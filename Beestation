BeeStation 的绝大多数功能通过单端点 /webapi/entry.cgi 暴露
nginx 将请求转发至 Unix 域套接字 synoscgi，再由配置路由到各共享库（.so）
{
  "SYNO.API.Auth": {
    "appPriv": "",
    "authLevel": 0,
    "disableSocket": false,
    "lib": "lib/SYNO.API.Auth.so",
    "maxVersion": 7,
    "methods": {
      "1": [
        {
         "logout": {
            "cgiProcReusable": true,
            "grantByUser": false,
            "grantable": true,
            "systemdSlice": ""
          }
        }
      ]
authLevel
0：无需认证
1：需要认证
2：无需认证，但已认证用户可见范围可能不同

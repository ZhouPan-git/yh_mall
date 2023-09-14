# yh_mall
1.数据库建表
   （1）用户表
   （2）商品表
   （3）商品种类表一
   （4）订单表
   （5）管理员表
   （6）商品种类表二
     (7)   订单详情表
2.业务需求，服务拆分：
   （1）init
     (2)  entity
     (3)  api
     (4)  gateway
     (5)  security
     (6)  goods
     (7)  order
     (8)  web
3.规范要暴露api接口(接入网关)
   （1）/yhgoods/goods/
     (2)  /yhorder/order/
     (3)  /yhsecurity/user/
     (4)  
4.前后端回传的数据格式（map.put）
     (1)  {code: 1
             data: 具体数据
            }
     (2)  {code:0
             msg: 错误信息
             }

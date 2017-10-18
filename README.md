# Odoo_Pay_Core_Code
Odoo实现微信扫码支付、微信条码支付、支付宝扫码支付、支付宝条码支付的核心代码

这只是最简单、核心的思路：发起交易、查询回传结果作出后续响应

可以进一步增加：
0:可以通过更多参数，进一步限制交易的内容：如过去时间、支付类型限制等
1:回传信息的签名验证
2:从回传信息中提取更多信息：银行信息、支付时间等等
3:可以从回传信息中提取不同的响应码，作出更细致的后续响应，如：系统错误、余额不足等等支付结果的响应
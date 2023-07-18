# 使用Javascript SDK 实现拼图验证
默认在WAF web acl中，直接对被保护的资源使用 CAPTCHA 拼图 action, 就可以实现web 页面的CAPTCHA 拼图 保护

但是如果要实现自定义的一些逻辑，例如，同一个用户多次登陆失败后，弹出CAPTCHA 拼图验证，则需要使用SKD

这个repo 演示如何使用javascript 实现同一个用户多次登陆失败后，弹出CAPTCHA 拼图验证，验证成功后重新提供登录页面


# API 文档
https://docs.aws.amazon.com/zh_cn/waf/latest/developerguide/waf-js-challenge-api-fetch-wrapper.html

# RefreshXyhelperToV1api
本项目基于[RefreshToV1Api](https://github.com/Yanyutin753/RefreshToV1Api)二开，有且仅适配xyhelper的付费接入点。本项目不开源，开源项目请移步至：[RefreshToV1Api](https://github.com/Yanyutin753/RefreshToV1Api)
## 特别鸣谢
感谢Xyhelper的付费接入点！感谢Yanyutin753、Ink-Osier对于项目的付出和贡献！
## 更新说明
- 有且仅适配xyhelper的付费接入点
- 内置gpts，请勿添加gpt-4-gizmo-*模型，模型已内置
- 输入的key为: refresh_token
- 处理了模型的空回复，不再出现空回复
- 当发现429时，在限制时间内不可访问，减少频繁访问429导致的封号问题。
- 支持使用team额度，在refresh_token后加上account_id即可
- 支持获取account_id, 接口：/getAccountID, 请求头：Authorization : Bearer {refresh_token}, 提交方式 POST
## 联系方式
- 获取授权文件，或者需要购买xyhelper的付费接入点[(官方链接)](https://xyhelper.cn/access/)，欢迎与我联系！
- 找我拼单**付费接入点**赠送本项目授权
- **微信**: Csg1271932463

  <img src="https://github.com/realnoob007/ChatGPT-Share-Web/assets/37624778/8423d852-239d-4e09-a093-9359f3a7f7c5" width="320">

## 项目推荐
[ChatGPT-Share-Web](https://github.com/realnoob007/ChatGPT-Share-Web)

基于ChatGPT-Share开发的商业版镜像站的部署仓库，旨在提供完全代理ChatGPT官网，包含完整的用户系统，对接官方ChatGPT网站的全部功能，集成无缝支付系统，以及管理员后台面板，实现全面的站点管理。

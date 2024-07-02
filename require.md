# 营会接口 （分页列表）
## 优先级高
![image](https://github.com/zhenyitech/jingtan/assets/32808725/c445f834-fa8b-4738-92d3-8b1378d36c6f)
- 参数 分类筛选、活动时间范围筛选
- 返回 id，封面、标签、标题、副标题、营期日期、费用

# 营会接口 （详情）
## 优先级高  
![image](https://github.com/zhenyitech/jingtan/assets/32808725/e52d5dfe-72d4-4b40-a4a7-a94b403e38c0)
- 参数 分类筛选、活动时间范围筛选
- 返回 封面、标签、标题、副标题、活动日期、费用、报名人数（是否限时、限时过期时间、限时立减金额）

# 微信用户信息更新
## 优先级高
- 相关文档 https://developers.weixin.qq.com/miniprogram/dev/api/open-api/user-info/wx.getUserProfile.html
- user表补充微信userInfo相关字段
- 参数 rawData、signature、encryptedData、iv
- 返回 成功/失败状态


#微博备份查看工具

一个微博备份查看工具

# 数据对象格式
##weibo

 | 字段        | 字段类型    |  字段说明  |示例  |
 | --------   | -----:   | :----: | :----: |
 | idstr      | string      |   微博id    |3608015325999696|
 | user        | string      |   微博作者数字id    |3261134763|
 | created_at        | string      |   发布时间    |2013-08-05 19:15:50|
 | text        | string      |   微博正文    |这是一条微博|
 | source        | string      |   微博来源    |iPhone客户端|
 | reposts_count        | string      |   转发数    |12|
 | comments_count        | string      |   评论数    |12|
 | attitudes_count        | string      |   点赞数    |12|
 | retweeted_status        | array      |   如果有转发微博，这个数据结构和微博一致|12|
 | pic_urls        | array      |   如果有图片就存在，图片数组    |["http:\/\/ww1.sinaimg.cn\/thumbnail\/c260f7abjw1e7bzy4hbrqj20890dcgm8.jpg"]|
 
 ##user
 
| 字段        | 字段类型    |  字段说明  |示例  |
 | --------   | -----:   | :----: | :----: |
 | uid      | string      |   用户uid，全局唯一    |3261134763|
 | screen_name      | string      |   用户昵称，全局唯一    |刘亦菲|
 | location      | string      |   用户地区    |北京|
 | description      | string      |   用户简介    |你又来看我的微博了|
 | followers_count      | string      |   粉丝数    |50859841|
 | friends_count      | string      |   关注数    |197|
 | statuses_count      | string      |   微博数    |863|
 | favourites_count      | string      |   收藏的微博数    |7|
 | created_at      | string      |   注册时间    |2013-08-05 19:15:50|
 | verified_reason      | string      |   认证原因    |演员刘亦菲|
 | profile_image_url      | string      |   个人资料图    |http://tva2.sinaimg.cn/crop.0.0.180.180.180/c260f7abjw1e8qgp5bmzyj2050050aa8.jpg|
 | cover_image_phone      | string      |   手机版个人资料图    |http://ww1.sinaimg.cn/crop.0.0.640.640.640/9d44112bjw1f1xl1c10tuj20hs0hs0tw.jpg|
 | cover_image      | string      |   封面图    |http://ww1.sinaimg.cn/crop.0.0.640.640.640/9d44112bjw1f1xl1c10tuj20hs0hs0tw.jpg|
 | gender      | string      |   性别 f:女     |f|
 | bi_followers_count      | string      |   双关好友数    |f|




# To Do List
- 更新功能

- 翻页


# 标准资讯 cube 模板，2*n图 + 6文字资讯

## 介绍
标准资讯类模板，适合新闻资讯类场景。

## 使用
```
cubetool init <cubeid> -t https://github.com/ntt360/cube-tpl-news-2pic6text.git
```
或简写：
```
cubetool init <cubeid> -t ntt360/cube-tpl-news-2pic6text
```

## UI预览
![标准资讯类模板 UI 预览图](https://raw.githubusercontent.com/ntt360/cube-tpl-news-2pic6text/master/ui/ui.png)

## data格式
```json
{
  "img_list": [
    {
      "title": "6个热气球地点",
      "url": "https://news.g.360.cn/topicdetail/LtfVREa2LHS7Pj",
      "pic": "https://p1.ssl.qhimg.com/t011655f484b2470b81.jpg"
    },
    {
      "title": "原来就是个超级广告",
      "url": "https://news.g.360.cn/topicdetail/KtPYQES2LHz6Pj",
      "pic": "https://p0.ssl.qhimg.com/t016153b58712580b1c.jpg?size=261x178"
    },
    {
      "title": "太丢中国玩家脸了",
      "url": "https://news.g.360.cn/topicdetail/LdTUPkW2LHz6Qw",
      "pic": "https://p1.ssl.qhimg.com/t0180d09199eedff14c.jpg?size=324x224"
    },
    {
      "title": "免费领枪械皮肤",
      "url": "https://news.g.360.cn/topicdetail/LNjZPkm1NXO7Pw",
      "pic": "https://p1.ssl.qhimg.com/t01e5929c9897429afa.jpg"
    },
    {
      "title": "神秘大事件解析",
      "url": "https://news.g.360.cn/topicdetail/LAjdPkK1NXK7Pw",
      "pic": "https://p0.ssl.qhimg.com/t01eafd917d014eb765.jpg"
    },
    {
      "title": "找代练代价有多大？",
      "url": "https://news.g.360.cn/topicdetail/KAPXPkO1NXKDPj",
      "pic": "https://p1.ssl.qhimg.com/t014cf38cbd97280228.jpg?size=316x219"
    }
  ],
  "text_list": [
    { 
      "title": "Steam3月最虐心游戏，上线两周却好评如潮！玩家为何边受苦边叫好？",
      "url": "https://news.g.360.cn/topicdetail/LAfVRke2LHW5Ow"
    },
    {
      "title": "为不让大家外出，外国政府也是拼了！竟专门建服务器给学生玩游戏",
      "url": "https://news.g.360.cn/topicdetail/LNbXPkW2LHW5OD"
    },
    {
      "title": "死亡之舞成上单神器 版本三大适配英雄推荐",
      "url": "https://news.g.360.cn/topicdetail/KdTWQ0K2LHSCOT"
    },
    {
      "title": "《半条命：爱莉克斯》带动设备卖脱销，预载空间需67.3G",
      "url": "https://news.g.360.cn/topicdetail/MtTZREW2LHSCOD"
    },
    {
      "title": "LPL W4前瞻：豪门与新贵 IG能否坐稳榜首？",
      "url": "https://news.g.360.cn/topicdetail/KtbXQkO2LHOAOT"
    },
    {
      "title": "中华文化博大精深！一个字足以毁掉游戏，暴雪竟也能和漫威掐架",
      "url": "https://news.g.360.cn/topicdetail/MdLYPkG2LHOAOD"
    }
  ]
}
```

# API Reference

## Fetch Latest News

``` javascript
GET https://news-at.zhihu.com/api/4/news/latest

Response:
Content-type: application/json

Response Body:
 {
    "date": "20230425",
    "stories": [
        {
            "image_hue": "0xb39168",
            "title": "昆虫为什么要进化出蛹这种不利于生存的形态？",
            "url": "https://daily.zhihu.com/story/9760754",
            "hint": "法小喵 · 4 分钟阅读",
            "ga_prefix": "042507",
            "images": [
                "https://picx.zhimg.com/v2-4e93be3339e9994d42de8855b947ea2b.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760754
        },
        {
            "image_hue": "0x6b8099",
            "title": "如果汉字失传了，释读它的难度有多大？",
            "url": "https://daily.zhihu.com/story/9760759",
            "hint": "黄鼠狼精Morrica · 1 分钟阅读",
            "ga_prefix": "042507",
            "images": [
                "https://pica.zhimg.com/v2-099f912c8550c34c34218bab4b2fae61.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760759
        },
        {
            "image_hue": "0x4d5b22",
            "title": "博物馆中令你最震惊的一件文物是什么？",
            "url": "https://daily.zhihu.com/story/9760767",
            "hint": "王盛 · 1 分钟阅读",
            "ga_prefix": "042507",
            "images": [
                "https://pica.zhimg.com/v2-48a37db57d2ee7cf5ece74a380602471.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760767
        },
        {
            "image_hue": "0xb3a57d",
            "title": "前电脑时代的建筑图纸是什么样的？是怎么画成的？",
            "url": "https://daily.zhihu.com/story/9760775",
            "hint": "知乎用户 · 3 分钟阅读",
            "ga_prefix": "042507",
            "images": [
                "https://picx.zhimg.com/v2-80c3d23a94bb839ecf703ea42eb6f464.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760775
        },
        {
            "image_hue": "0x64818f",
            "title": "在你所处的领域中，有哪些想象已经变成了现实？",
            "url": "https://daily.zhihu.com/story/9760778",
            "hint": "极萨学院冷哲 · 5 分钟阅读",
            "ga_prefix": "042507",
            "images": [
                "https://pic1.zhimg.com/v2-17dc46b57e9520a85e8da8a36614ca46.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760778
        },
        {
            "image_hue": "0xb3aa7d",
            "title": "瞎扯 · 如何正确地吐槽",
            "url": "https://daily.zhihu.com/story/9760785",
            "hint": "VOL.3090",
            "ga_prefix": "042506",
            "images": [
                "https://pic1.zhimg.com/v2-33e239053063d36376a5bc603e005d38.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760785
        }
    ],
    "top_stories": [
        {
            "image_hue": "0x935755",
            "hint": "作者 / 今夕何夕",
            "url": "https://daily.zhihu.com/story/9760718",
            "image": "https://picx.zhimg.com/v2-5e21ac17e9c4266261e28282433de0b2.jpg?source=8673f162",
            "title": "请问在中国历史上，洛阳和长安各自作为首都的利弊有哪些？",
            "ga_prefix": "042107",
            "type": 0,
            "id": 9760718
        },
        {
            "image_hue": "0xb39168",
            "hint": "作者 / 法小喵",
            "url": "https://daily.zhihu.com/story/9760754",
            "image": "https://picx.zhimg.com/v2-03914594de86953ffe60b7017fb6e650.jpg?source=8673f162",
            "title": "昆虫为什么要进化出蛹这种不利于生存的形态？",
            "ga_prefix": "042507",
            "type": 0,
            "id": 9760754
        },
        {
            "image_hue": "0x2e3022",
            "hint": "作者 / 思思安",
            "url": "https://daily.zhihu.com/story/9759918",
            "image": "https://picx.zhimg.com/v2-bd0852aec02e17f8caa2facf9194d201.jpg?source=8673f162",
            "title": "《甄嬛传》里的淳儿到底是真的单纯还是有心计藏得深？",
            "ga_prefix": "042407",
            "type": 0,
            "id": 9759918
        },
        {
            "image_hue": "0x22291d",
            "hint": "作者 / 十四花生",
            "url": "https://daily.zhihu.com/story/9760727",
            "image": "https://picx.zhimg.com/v2-cf32f0c2bfe8ed0c98ecc24b46dfd797.jpg?source=8673f162",
            "title": "小事 · 你经历过的最有趣的事是什么呀？",
            "ga_prefix": "042307",
            "type": 0,
            "id": 9760727
        },
        {
            "image_hue": "0xb39a7d",
            "hint": "作者 / 高远",
            "url": "https://daily.zhihu.com/story/9760715",
            "image": "https://pica.zhimg.com/v2-a8896eb09b82cff7daf05d44fdbd0b04.jpg?source=8673f162",
            "title": "小事 · 你遇过的最温暖的瞬间是什么？",
            "ga_prefix": "042207",
            "type": 0,
            "id": 9760715
        }
    ]
}
```

- `date` : 日期
- stories: 当日新闻
  - `image_hue`:图像色彩，用不到可以不管
  - `title` : 新闻标题
  - `url`:文章内容的url，可以用webview直接加载内容
  - `hint`:作者和预计的阅读时间，用在标题下面示意
  - `images` : 图像地址（官方 API 使用数组形式。目前暂未有使用多张图片的情形出现，曾见无 `images` 属性的情况，请在使用中注意 ）
  - `ga_prefix` : 供 Google Analytics 使用，用不到不管
  - `type` : 作用未知
  - `id` : 文章的id
- `top_stories` : 界面顶部的Banner图



# Fetch News Detail

```javascript
GET https://news-at.zhihu.com/api/4/news/{{id}}

Response Body:
{
    "body":"[HTML CODE]",
    "url":"https://daily.zhihu.com/story/9772237",
    "image":"https://pica.zhimg.com/v2-75f1ff5b9eb01dc392d36b3727323917.jpg?source=8673f162",
    "share_url":"http://daily.zhihu.com/story/9772237",
    "js":[],
    "ga_prefix":"051307",
    "images":[
        "https://pic1.zhimg.com/v2-284b9581e5ea16eca7c839349c6ca70b.jpg?source=8673f162"
    ],
    "type":0,
    "id":9772237,
    "css":[
        "http://news-at.zhihu.com/css/news_qa.auto.css?v=4b3e3"
    ]
}
```





# Past News

```javascript
GET https://news-at.zhihu.com/api/4/news/before/{{Date}}
Example:
GET https://news-at.zhihu.com/api/4/news/before/20230425
Date must before '20130520'

Response Body:

 {
    "date": "20230424",
    "stories": [
        {
            "image_hue": "0x2e3022",
            "title": "《甄嬛传》里的淳儿到底是真的单纯还是有心计藏得深？",
            "url": "https://daily.zhihu.com/story/9759918",
            "hint": "思思安 · 8 分钟阅读",
            "ga_prefix": "042407",
            "images": [
                "https://picx.zhimg.com/v2-41a7ccd9640b5bf56cf0a5077e4d0baa.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9759918
        },
        {
            "image_hue": "0xb39979",
            "title": "怎么看待国内很多时候将越南语和泰语归入汉藏语系？",
            "url": "https://daily.zhihu.com/story/9759864",
            "hint": "知乎用户 · 2 分钟阅读",
            "ga_prefix": "042407",
            "images": [
                "https://pica.zhimg.com/v2-74e308eb00598a42c979ac033aaec602.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9759864
        },
        {
            "image_hue": "0xb38f7d",
            "title": "古代诗词是如何被记录并传播开来的？",
            "url": "https://daily.zhihu.com/story/9759872",
            "hint": "豆子 · 2 分钟阅读",
            "ga_prefix": "042407",
            "images": [
                "https://picx.zhimg.com/v2-3c73d8a7d3ca99d5afc715be6ca5f437.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9759872
        },
        {
            "image_hue": "0x636363",
            "title": "历史上中国死了那么多人都土葬，为什么没感觉有那么多坟墓？",
            "url": "https://daily.zhihu.com/story/9759880",
            "hint": "郁练级 · 3 分钟阅读",
            "ga_prefix": "042407",
            "images": [
                "https://picx.zhimg.com/v2-2185b708171b5178d1597bffd00b142c.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9759880
        },
        {
            "image_hue": "0x14130c",
            "title": "如果从远古开始温度一直适宜，人类有可能进化成不穿衣服的生物群体吗？",
            "url": "https://daily.zhihu.com/story/9760886",
            "hint": "赵泠 · 1 分钟阅读",
            "ga_prefix": "042407",
            "images": [
                "https://pic1.zhimg.com/v2-75d18581cd391e6f32635e5ae8b63d8c.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9760886
        },
        {
            "image_hue": "0x293625",
            "title": "瞎扯 · 如何正确地吐槽",
            "url": "https://daily.zhihu.com/story/9759884",
            "hint": "VOL.3089",
            "ga_prefix": "042406",
            "images": [
                "https://pic1.zhimg.com/v2-3f42af35cf6c9335d7eba6b50d2efe1c.jpg?source=8673f162"
            ],
            "type": 0,
            "id": 9759884
        }
    ]
}

```

# Extra

```javascript
GET https://news-at.zhihu.com/api/4/story-extra/{{news_id}}

Response Body:
{
    "long_comments": 0,
    "popularity": 64,
    "short_comments": 13,
    "comments": 13
}
```

- `long_comments` : 长评论总数
- `popularity` : 点赞总数
- `short_comments` : 短评论总数
- `comments` : 评论总数


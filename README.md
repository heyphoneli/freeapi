

# freeapi
一个提供稳定聚合api接口。免费，且长期维护，持续添加新接口！
## 目录
 - [接口列表](#catalogue)
 - [一、古诗](#poetry)
    - [1、获取古诗列表](#poetry1)
    - [2、获取古诗名句]()
    - [3、获取古诗详情]()
    - [4、获取古诗作者/诗人]()
    - [5、获取古诗作者/诗人相关事件]()
 - [二、成语大全]()
    - [获取成语列表]()
 - [三、万年历]()
    - [1、获取某一年内每天基本信息]()
    - [2、获取某一个月内每天基本信息]()
    - [3、获取某一天基本信息]()
    - [4、获取某一天详细信息]()
## 接口列表 <div id="catalogue"/>
#### 一、古诗 <div id="poetry"/>
1、获取古诗列表 <div id="poetry1"/>
 - 接口说明：根据条件获取古诗列表
 - 请求地址：/poetry
 - 请求参数：
   - page：当前页数
   - size：分页大小，默认每页10条
   - author：作者/诗人，非必需
   - content：模糊搜索，标题或内容包含content，非必需
   - type：类型（诗/词/歌/赋），非必需
   - tag：标签，非必需
   - year：朝代，非必需
- 返回数据：
   - analyse：赏析
   - author：诗人/作者
   - content：内容
   - explain：释义
   - tags：标签
   - title：标题
   - trans：译文
   - year：朝代
- 请求示例：
   - /poetry?page=1&author=李白&content=花&size=2&tag=唐诗三百首
- 返回示例：
```
{
    "code": 200,
    "data": [
        {
            "analyse": "",
            "author": "牟融",
            "content": "几度乘闲谒梵宫，此郎声价重江东。贵侯知重曾忘势，\n闲客频来也悟空。满地新蔬和雨绿，半林残叶带霜红。\n",
            "explain": "<div class=\"conview conview_zhu\">\n <div></div>\n</div>",
            "pinyin": "jǐ dù chéng xián yè fàn gōng ，cǐ láng shēng jià zhòng jiāng dōng 。guì hóu zhī zhòng céng wàng shì ，\nxián kè pín lái yě wù kōng 。mǎn dì xīn shū hé yǔ lǜ ，bàn lín cán yè dài shuāng hóng 。\n",
            "tags": "",
            "title": "送报本寺分韵得通字",
            "trans": "",
            "year": "汉朝"
        }
    ],
    "msg": ""
}
```
2、获取古诗名句
 - 接口说明：根据id获取古诗详情
 - 请求地址：/poetry/:id
 - 请求参数：
   - id：古诗id
   - size：分页大小，默认每页10条
   - author：作者/诗人，非必需
   - content：模糊搜索，标题或内容包含content，非必需
   - type：类型（诗/词/歌/赋），非必需
   - tag：标签，非必需
   - year：朝代，非必需
- 返回数据：
   - analyse：赏析
   - author：诗人/作者
   - content：内容
   - explain：释义
   - tags：标签
   - title：标题
   - trans：译文
   - year：朝代
- 请求示例：
   - /poetry?page=1&author=李白&content=花&size=2&tag=唐诗三百首
   
 3、获取古诗详情
 - 接口说明：根据id获取古诗详情
 - 请求地址：/poetry/:id
 - 请求参数：
   - id：古诗id
   - size：分页大小，默认每页10条
   - author：作者/诗人，非必需
   - content：模糊搜索，标题或内容包含content，非必需
   - type：类型（诗/词/歌/赋），非必需
   - tag：标签，非必需
   - year：朝代，非必需
- 返回数据：
   - analyse：赏析
   - author：诗人/作者
   - content：内容
   - explain：释义
   - tags：标签
   - title：标题
   - trans：译文
   - year：朝代
- 请求示例：
   - /poetry?page=1&author=李白&content=花&size=2&tag=唐诗三百首
- 返回示例：
4、获取古诗作者/诗人

5、获取古诗作者/诗人相关事件


       

     


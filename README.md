# 一个假的qq音乐demo qq_music_spa

> 我可能做了一个假的qq音乐demo， 本demo参考`https://y.qq.com`开发的，难怪跟网上其他人的案例界面不一样。。。Orz

## Build Setup

``` bash
# 安装依赖
npm install

# serve with hot reload at localhost:8080 启动服务
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

```
## 功能实现

首页：banner滚动效果实现，电台下级页面未接入（配的活动页或列表页，情况太复杂后续优化）

排行榜：完成榜单列表和榜单歌曲list，并可播放榜单歌曲

搜索页：手动搜索功能完成，推荐热搜词未添加搜索入口

播放页：歌曲正常播放，歌词同步高亮／滚动

搜索结果页：搜索结果正常显示／跳转到对应播放页面

搜索历史去重／排序

自定义｀localstorage｀方法，添加／删除／清空数据；

优化｀localstorage｀可存／取数组类型（通过序列化和反序列化）


> 个人闲暇时间里做的，希望跟大家共同进步————持续更新／优化

## 目前存在的问题

组件划分还不够精细，这个需要更多经验和对产品的理解

代码优化还有待加强

## 优点

用到了比较新且全面的`Vue`相关的技术栈，

1. "vue": "^2.1.10",
2. "vue-awesome-swiper": "^2.3.2",
3. "vue-resource": "^1.2.0",
4. "vue-router": "^2.2.0",
5. "vuex": "^2.1.2"

代码格式比较整齐（换过一次IDE，可能个别文件缩紧不统一，见到时候会调整回来）


## 案例截图（早期的截图——功能不完善——具体效果大家自己在本地clone代码运行）
![image](https://github.com/chengjun2014/qq_music/blob/master/music.gif)


![image](https://github.com/chengjun2014/qq_music/blob/master/playing.gif)





# 数据管理方案对比

## 关键结果
- [ ] 实现react-redux

## 任务
- [ ] 画出当前项目数据流动图
- [ ] kryfe-lib/lib/fetchHelper/fetchRequest.js代码编写
- [ ] fetch.js代码编写
- [ ] 函数式编程：编写管道组合相关代码并画图

- [ ] 实现react-redux
  - [ ] 能说出来为什么使用react-redux(implementation: native vs react-redux)
    - [ ] 在不使用react-redux的情况下实现xxx
    - [ ] 结合react-redux的情况下实现xxx
  - [ ] 能说出来react-redux的实现原理
    - [ ] 

```
(...args) => mid1(mid2(mid()))

p0: (...args) => mid1(mid2(...args))

p1: (...args) => p(mid3(...args))

mid3 next = dispatch
mid2 next = mid3
mid1 next = mid2 
```

## 参考资料

[React世界的函数式编程(Functional Programming)](https://zhuanlan.zhihu.com/p/26174525)
[Redux原理与函数式编程有着怎样的不解之缘？](https://mp.weixin.qq.com/s/_7iarJ0PnBjd_w9ARmKcPw)
[函数式编程在Redux/React中的应用](https://tech.meituan.com/2017/10/12/functional-programming-in-redux.html)
[浅谈前端响应式设计](https://mp.weixin.qq.com/s/vsViuSHAFzuWTD5aGC6c8g)
[浅谈前端响应式设计(二)](https://mp.weixin.qq.com/s/s0odIchpAsvcrkV0c80htw)
[单页应用的数据流方案探索](https://zhuanlan.zhihu.com/p/26426054)
[复杂单页应用的数据层设计](https://zhuanlan.zhihu.com/p/24677176)
[流动的数据——使用 RxJS 构造复杂单页应用的数据逻辑](https://github.com/xufei/blog/issues/38)
[前端如何更好的实现接口的缓存和更新?](https://www.zhihu.com/question/40035517/answer/84372581)
[ReactiveDB](https://github.com/teambition/ReactiveDB)
[Teambition 数据层重构经验分享](https://slides.com/yinan/deck/fullscreen)
[如何增强单页应用的体验](https://github.com/xufei/blog/issues/35)
[在前端开发过程中，你遇到过最复杂的状态管理场景是什么，并且是如何解决或者管理该场景下的状态的？](https://www.zhihu.com/question/295450089)
[【第1910期】如何设计实现 h5 页面搭建-数据模型](https://mp.weixin.qq.com/s/Fyl3SMHjv3ROw9QUBdwutA)
[写在2017的前端数据层不完全指北](https://mp.weixin.qq.com/s/APolKAJ1DpPKaL42qS8rOQ)
[DaoCloud 基于 RxJS 的前端数据层实践](https://zhuanlan.zhihu.com/p/28958042)
[前端 MVVM 模式中的数据层（Model）](https://mp.weixin.qq.com/s/e9HNW2t18gvRVFncTiL8Xw)
[【第1959期】面向 Model 编程的前端架构设计](https://mp.weixin.qq.com/s/peLNXa_PLQTfhTtLya3cpg)
[hodux：极简响应式React Hooks数据流](https://zhuanlan.zhihu.com/p/101912754)
[漫谈前端数据层](https://zhuanlan.zhihu.com/p/165213964)
[都说数据处理比较难，那么前端数据处理难点在哪里？](https://www.zhihu.com/question/57152155/answer/152324864)
[前端数据流哲学](https://zhuanlan.zhihu.com/p/33382396)
[数据模型是如何助力前端开发的](https://mp.weixin.qq.com/s?__biz=MjM5MTA1MjAxMQ==&mid=2651233203&idx=1&sn=d666068b9e14238c55995fad75b61a21&chksm=bd4942378a3ecb2119d54ab6acc2d2eed2f5b73f888a7da63bd1d88f2fd3ab828bafaaf45de5&scene=21#wechat_redirect)
[从零实现 redux 和 react-redux](https://juejin.cn/post/6844904100308467726)
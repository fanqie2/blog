# 小程序开发记录清单

### 禁止页面拉动
- 在微信小程序中，用力向下拉动定不会出现一段空白，在某些需求下，需要禁止拉动。
可以在page里对应的json文件里加上`"disableScroll":true`.需要注意的是，在app.json里写这个属性不会生效。`enablePullDownRefresh（下拉刷新）和disableScroll同时为true时，下拉刷新不会生效`
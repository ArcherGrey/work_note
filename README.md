# 工作记录

架构：
- MVC
 
前端：
- jquery 
- easyui 
- bootstrap
- mui

后端：
- C# 调用服务 LINQ WCF 
- C++ 提供基础服务 PROTOBUFFER

数据库：
- mysql

bug:
- jquery easyui 控件功能失效 （修改功能相关逻辑）
- 初始化参数错误导致的功能失效或异常（修改初始化参数）
- 逻辑错误导致的功能失效或者异常（修改错误逻辑）
- 控件相互遮挡，显示问题（调整样式）
- 中英文环境显示错误（修改资源文件）
- 样式变化错误（修改样式）
- 添加校验框
- 多线程文件操作导致死锁，前端等待时间过长，使页面崩溃（修改为单线程）
- 任务顺序错误（修改sql获取正确的任务队列）
- 每秒对后端发送时间同步请求，请求过于频繁导致前端操作卡顿（修改为初次进入是获取时间差，通过时间差修正本地时间）



开发：
- 客户端需要和服务端时间显示一致（通过后端提供的接口同步时间）
- 添加逻辑所需的提示框
- 修改 easyui 的时间框控件，可以根据配置信息修改时间格式
- 使用 protobuffer 根据协议和后端交互
- ajax 交互
- jsonp 跨域
- 使用 `bootstrap` 将 easyui 替换（主要是模态框，涉及日期选择框、表格）
- 传输任务中断，暂停，继续
- mui 移动端开发

性能优化：
- 翻页卡顿，easyui表格控件性能不佳，超过一百条翻页卡顿明显
- 使用固定版本浏览器不存在兼容问题，`jquery` 意义不大
- js文件放在最后导入，避免下载阻塞渲染


# 股市总结

- 突然下跌的股票不能接着买，最好等他稳定后成交量下滑到最低买入
- 年报，中报之前是机会
- 周四国债4天，月末季度末年末
- 成交量第一次放大上涨，继续上涨机会大，上涨一段时间后成交量放大后市大概率下跌
- 实业价格水分不大，容易回升：例如比亚迪；虚拟行业水分大，风险大：例如三六零
- 一般不会突然下跌，会阴跌再大跌，不用急入场

|基本：104000|
|-----|
|zfb: 19000|
|xxx: 10000|
|总计：133000|

实际：

|日期|金额|变换|
|:------:|:------:|:------:|
|2018-11-2|106391.06 |  0  |
|2018-11-6|106386.01 |-5.05|
|2018-11-22|106439.55|48.49|


# gz

- 2017 8500
- 2018 11000

|日期|sq|sh|
|:------:|:------:|:------:|
|2017/07-2018/06|115500|94686.75|
|2018/07-2019/06|预计 150000 |预计 120000|


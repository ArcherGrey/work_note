
# HTML

- `checkbox` 勾选后没有 `checked="checked"`
- 访问 `iframe` 中的内容，通过 `contentWindow` 获取 `iframe` 标签，然后再通过 `document.get...` 获取内部信息（注意在本地测试时由于是 `file` 协议导致跨域而无法访问，需要在 `iis` 中通过 `http` 协议访问）
- 防止浏览器提示保存密码或自动填充密码 可以在 `input` 属性里添加 `autocomplete="new-password"`
- 后端调用 `SetWindowPos` 实现浏览器窗口顶置

# javascript
- `ajax` 同步不生效：`jsonp`不能同步，所有跨域操作都不能同步

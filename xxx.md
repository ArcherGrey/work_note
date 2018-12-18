
# HTML

- `checkbox` 勾选后没有 `checked="checked"`
- 访问 `iframe` 中的内容，通过 `contentWindow` 获取 `iframe` 标签，然后再通过 `document.get...` 获取内部信息（注意在本地测试时由于是 `file` 协议导致跨域而无法访问，需要在 `iis` 中通过 `http` 协议访问）

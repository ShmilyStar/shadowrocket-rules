# 🚀 shadowrocket-rules


## 规则下载

- **黑名单blacklist规则**：
  - [https://cdn.jsdelivr.net/gh/ShmilyStar/shadowrocket-rules@master/blacklist.conf](https://cdn.jsdelivr.net/gh/ShmilyStar/shadowrocket-rules@master/blacklist.conf)
- **直链（DIRECT）规则**：
  - [https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_direct_list.module](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_direct_list.module)
  - [https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_direct_list.module](https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_direct_list.module)
- **代理（PROXY）规则**：
  - [https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_proxy_list.module](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_proxy_list.module)
  - [https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_proxy_list.module](https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_proxy_list.module)
- **屏蔽（REJECT）规则**：
  - [https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_reject_list.module](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_reject_list.module)
  - [https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_reject_list.module](https://cdn.jsdelivr.net/gh/GMOogway/shadowrocket-rules@master/sr_reject_list.module)
>每类规则提供了二个链接，一个需要代理才能访问，一个可以直接访问，请根据实际情况选择，只是jsdelivr会延迟12小时，但对于几万条的规则来说，没什么影响。

- **刷新CND缓存**：
  
- https://cdn.jsdelivr.net/
- 切换为
- https://purge.jsdelivr.net/

## 帮助文档

- [01.shadowrocket_configure.md](https://github.com/GMOogway/shadowrocket-rules/blob/master/docs/01.shadowrocket_configure.md)，比较全面的介绍了shadowrocket小火箭的配置文件
- [02.shadowrocket_update_modules.md](https://github.com/GMOogway/shadowrocket-rules/blob/master/docs/02.shadowrocket_update_modules.md)，介绍了如何手动或自动更新shadowrocket小火箭规则模块
- [03.shadowsocks_tiny.conf](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/docs/03.shadowsocks_tiny.conf)，一个小火箭的极简配置，不到20行，容易修改编辑吧？再配上本项目提供的规则，即可精准分流、愉快上网

## 贡献代码？

通常的情况下，对 [factory 目录](https://github.com/GMOogway/shadowrocket-rules/tree/master/factory) 下的 6 个 .txt 文件做对应修改即可，可以对三个规则作添加或删除。

# AniColle

- 何これ？
- アニコレ！ ٩(๑´3｀๑)۶

两年前(?)开的大坑，现在以另一种形式补起来。

这个程序主要用来收藏用户现在正在收看的番剧，并提供更新检测功能。

番剧列表可根据用户需要自主添加或导入他人制作的番剧数据。

*这是一个初期版本！！*

*这是一个初期版本！！*

*这是一个初期版本！！*

## 安装与使用

很简单，clone下这个版本库，运行 `pip install -r requirements.txt`

然后 `run.py -h` 就好喇！

目前支持 漫游BT服务器 的更新检查，添加番剧时将检索关键词一栏写上要在 漫游 搜索的番剧名字即可。

修改服务器配置请用 `anicolle/config.py` 文件，修改运行模式请设置 `ANICOLLE_MODE` 系统变量。

## 开发情况

- [x] 原型开发

- [ ] 导入/导出 功能

- [ ] 更新检查系统模块化

- [ ] ~~多种数据库模式 (SQLite/MySQL) 的支持~~

- [ ] ~~完全封装的桌面客户端~~ (*已经有webui的支持，暂不考虑*)

- [ ] 适配的移动客户端

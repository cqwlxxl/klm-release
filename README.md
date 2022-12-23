# klm-release

#### 介绍

Kugou Lyrics Maker 发布页

krc、ksc、lrc歌词制作工具，本工具完全免费，可以制作酷狗krc歌词，也能保存成lrc歌词。更多方便的功能请在软件中体验

#### 版本更新

##### 1.0.1.0

1.  new: 区间制作功能(对已制作完成的一行或多行，重新进行制作)
2.  new: 导入krc恢复制作状态功能
3.  new: 新增行、删除行、编辑行功能

##### 1.0.0.22

1.  fix: 未录入歌词，点击读音/翻译按钮崩溃问题
2.  fix: 个性化中读音对照颜色恢复默认错误问题
3.  new: \*.ksc格式支持(小灰熊字幕/KBuilder Tools)，支持保存和转换功能
4.  mod: 优化拖动音量条不流畅问题

##### 1.0.0.21

1.  new: 读音/翻译双语歌词制作功能

##### 1.0.0.20

1.  fix: 后缀名判断优化，避免大写后缀、大小写混合后缀无法正常处理问题
2.  fix: 修正为保存lrc时，首行0开始才加入\[00:00.00\]的空行
3.  fix: 制作界面焦点判断错误
4.  new: 批量转换为lrc功能
5.  new: 歌词录入时，可通过拖入krc/lrc获取歌词文本
6.  mod: 使用qt自带解压缩替代zlib，优化编解码

##### 1.0.0.19

1.  new: 正常平均和快速平均合并为平均(若编辑行未开始，则平均开始时间为上行末字结束时间；若编辑行已开始，则平均开始时间为编辑行首字开始时间)
2.  new: 保存lrc时可替换指定文本
3.  new: 保存lrc时可添加指定附加后缀名(解决foobar2000匹配lrc优先krc问题)
4.  mod: 末字按下，自动切下行

##### 1.0.0.16

1.  fix: 快速平均时，\[x,y\]标签中x始终会为0

##### 1.0.0.15

1.  fix: 快退时，会超过完成行末字的结束时间
2.  fix: 大写后缀名歌曲无法识别问题
3.  fix: 偶尔加载歌曲无法成功问题
4.  fix: 重新拖入相同歌曲未重新加载问题
5.  fix: krc编码的歌词从utf-8改为utf-8 bom
6.  new: 制作界面个性化定制功能
7.  new: 制作界面快捷键自定义功能
8.  new: 歌曲进度和文件名展示
9.  new: 退出时保存窗口大小和位置功能
10.  new: 保存手机酷狗使用的krc功能(仅文件名带md5，krc内容一致的)
11.  new: 软件图标重新设计
12.  new: 添加帮助(更新日志/使用说明/常见问题)
13.  new: 第三方来源展示
14.  new: 添加快速平均分配功能(本行无需开始，自动以上行末字结束时间作为平均分配的开始)
15.  new: 无效歌曲判断
16.  new: 未播放时，禁止→、↓、平均分配操作
17.  new: 点击了播放/暂停/停止后，自动将焦点切换到歌词编辑界面，方便操作
18.  new: 增加繁体中文语言
19.  mod: 优化歌曲加载状态和播放播放状态
20.  mod: 修改歌词后，自动滚动到当前行

##### 1.0.0-pre12

1.  fix: 高分屏封面显示不清晰问题
2.  add: 加入除\*.mp3外的其他歌曲格式支持(\*.flac、\*.wav、\*.ape、\*.ogg、\*.m4a)
3.  add: krc的调整偏移功能
4.  add: 歌曲md5计算并写入krc
5.  add: 更新翻译，并添加qt官方翻译文件
6.  mod: 封面无效或无封面时显示无封面

##### 1.00-pre9

1.  歌词制作完成后，可按←或↑继续制作
2.  现在制作中可以修改歌词了
3.  封面显示保持比例，优化了歌词文本的预处理

##### 1.00-pre6

1.  修复\[x,y\]标签中y标签错误的问题

##### 1.00-pre4

1.  增加配置文件，翻译文件(目前只有简体中文)，歌曲封面展示，音量调节
2.  其他细节性优化

##### 1.00-pre1

1.  基本功能完成

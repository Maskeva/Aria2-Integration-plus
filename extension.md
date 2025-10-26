关于此扩展
[Help Translate](https://github.com/Maskeva/Aria2-Integration-plus/tree/master/App/_locales) | [Submit a Bug or Feedback](https://github.com/Maskeva/Aria2-Integration-plus/issues) | [Contribute or Star This Project](https://github.com/Maskeva/Aria2-Integration-plus)

由于原版作者不再更新,这里fork一份来更新下,感谢原作者 https://github.com/RossWang/Aria2-Integration 

特色:
1. 直接取代Firefox内置的下载窗口，不需要先点击内置的下载按钮或使用右键菜单
2. 可以传递Headers (referrer、cookies) 到Aria2
3. 自动开启和关闭Aria2c

已知问题:
1. 不支持FTP下载。
2. 因为Aria2c可能还没开好，有时会在按下下载按钮后显示错误讯息。
3. Firefox内置的下载Firefox官方不开放传递referer和cookies

=====================================================

你需要自行下载Aria2，完成选项中的协议、地址、端口、接口并保存才能开始使用

如果你不想要手动启动Aria2, 你可以自己写一个在后台启动Aria2的程序并注册到系统中的 'autostart' 或 'uri scheme'
你可以在这里找到示例文件

=====================================================
甚么是Aria2？
https://aria2.github.io/

此扩展使用了 Mayswind 的 AriaNg.
https://github.com/mayswind/AriaNg
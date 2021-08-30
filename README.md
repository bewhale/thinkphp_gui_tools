# 停止下载





# thinkphp_gui_tools

本项目是采用 JDK8 + javafx 开发的 ThinkPHP 图形化综合利用工具， 参考了其他大佬项目的部分代码。

JDK8可以直接运行，JDK11 因为去除了javafx这个依赖，需要自己再加上参数加入模块

```
java -Dfile.encoding="UTF-8" --module-path "C:\Program Files\Java\javafx-sdk-11.0.2\lib" --add-modules "javafx.controls,javafx.fxml,javafx.web" -jar "xxx.jar"
```

* 支持大部分ThinkPHP漏洞检测,整合20多个payload
* 支持部分漏洞执行命令
* 支持单一漏洞批量检测
* 支持TP3和TP5自定义路径日志遍历
* 支持部分漏洞一键GetShell
* 支持设置代理和UA

![](https://raw.githubusercontent.com/bewhale/thinkphp_gui_tools/main/img.png)

![](https://raw.githubusercontent.com/bewhale/thinkphp_gui_tools/main/img1.png)

![](https://raw.githubusercontent.com/bewhale/thinkphp_gui_tools/main/img2.png)

# 参考项目
https://github.com/SkyBlueEternal/thinkphp-RCE-POC-Collection  
https://github.com/Lucifer1993/TPscan  
https://github.com/fupinglee/JavaTools  
https://github.com/xinyu2428/TDOA_RCE  

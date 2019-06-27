# linux_log

实现一个日志采集模块，包括如下功能：

1、采集/home/ts/ts_prg/probe/log/下文件

2、导出mysql的tckr库

3、调用一些linux命令，将命令回显保存为文件，命令暂定包括：

        ps ax

        ifconfig

        ping 172.20.0.2 -c 4

        free

        ......待补充

4、将所采集到的日志文件生成一个压缩包(必须添加一个固定的解压缩密码)，命名格式：log_年月日时分秒，存储到/xiaocao_data/log

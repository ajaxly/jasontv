# jasontv
waipn
l2tp 环境搭建
1.使用wget  https://github.com/ajaxly/jasontv/blob/main/l2tp.sh 下载l2tp.sh

2. 查询位置：find / -name "l2tp.sh" （通常在当前目录下） 

3.确定运行权限：chmod a+x l2tp.sh 运行  sh l2tp.sh

4.执行指定操作 对秘钥 用户名 密码输入 确定即可  


5.如果ios高版本连接不上l2tp  需要修改（注释/删除sha2-truncbug=yes  但对以前版本有影响)
 修改方式 ：查找位置：grep -rsn "sha2-truncbug"  *  找出修改 结果显示例如：l2tp.sh:365:    sha2-truncbug=yes 
 
 6.即可完成



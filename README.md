# rust_os2022_log

7月5日-7月10日
因为还在进行实训，时间有限，完成《计算机组成与设计（RISC-V版）》第一、二章

7月18日
观看了前三节课程视频，了解了三叶虫OS,LibOS,隔离机制等

7月19日
完成了lab1的函数编写，没有想象中难，甚至都不需要操作系统知识

7月20日
完成了第四第五节课程的学习，感觉还是比较模糊，还是得多看几遍，还是直接看书做实验呢

7月21日
感觉变难了，虽然注释很详细，但lab2还是卡住了，我再看看代码吧

7月22日
完成了lab2，继续做下一个

7月23日
做lab3，迁移的代码有点多

7月24日
spawn应该等于fork()把父进程地址空间换为要执行的程序的地址空间
不仅要在儿子里面添加父进程，而且要在父进程添加子进程
sleep没有完成，说明yield_后没有返回
创建子进程时要添加上下文
将返回值设置为0证明成功
##项目介绍：
###项目名称：（oldboy选课系统）
###项目功能：
####分为 学员视角， 老师视角 ， 管理员视角

学员视角{
    （注册 登录  个人中心 选课 学习 上课）
              登录 就是登录
              注册： 填写 资料 信息 完成注册
              选课 =》 选择课程
              学习 =》 查看所在班级 , 上课记录 , 以及查看老师批改作业后的成绩，查看我的课程===》{  进入课程进行学习   }
}

老师视角{
    （登录  不能注册（只能由管理员创建） 查看班级）
              登录 就是登录
              查看学员 =》输入班级编号 =》 得到 该班级所有的学生信息 = 》 可以修改学生成绩
              开始上课 => 输入班级编号 =》 可以上课（假的）
}
管理员视角{
     (校区管理，课程管理，讲师管理，班级管理，学员管理)
            校区管理 =》 查看校区 ， 创建校区 ， 修改校区
            课程管理 =》 查看课程 ， 创建课程 ， 修改课程
            讲师管理 =》 查看讲师 ， 创建讲师 ， 修改讲师
            班级管理 =》 查看班级 ， 创建班级 ， 修改班级
            学员管理 =》 查看学员 ， 关联班级（就是将学员和班级关联 （确认学员的班级））
}

###目录结构介绍：

"""
selection/
|-- bin/
|   |-- __init__.py      包文件
|   |-- start.py         程序入口文件
|-- core/           ------程序主要文件
|   |-- __init__.py           包文件
|   |-- admin_view.py         管理员视图文件
|   |-- main.py               主程序
|   |-- school_view.py        学校视图文件
|   |-- student_view.py       学生视图文件
|   |-- teacher_view.py       老师视图文件
|-- conf                   配置文件
    |-- setting.py         日志配置文件
|-- db            数据存放的地方
|   |-- ...       数据库
|-- include/      接口文件（interface）
|   |-- __init__.py     包文件
|   |-- classroom.py       班级接口
|   |-- course.py          课程接口
|   |-- school.py          学校接口
|   |-- teacher.py         讲师接口
|-- modules/                程序公共调用模块存放
|   |-- __init__.py        包文件
|   |-- databases.py       数据库模块
|   |-- UserAuth.py        用户逻辑模块
|-- README.md
|-- 选课系统作业.pdf       项目流程图
"""

## 作业及学习时所写

    选课系统

    python3 index.py  启动主程序


## 作者博客
https://www.cnblogs.com/rianley
## python交流群
  程序员的个人修养 687226766


## 项目截图
自行参考pdf文档！
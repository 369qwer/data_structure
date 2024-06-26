# 数据结构

基于《数据结构（C语言版）》清华大学出版社


# 目录
- [数据结构](#数据结构)
- [环境](#环境)
- [可能遇到的问题](#可能遇到的问题)
  - [CMake的安装](#CMake的安装)
- [配置](#配置)
- [后续提交](#后续提交)


# 环境

windows 10

Visual Studio 2019

cmake  3.29.2

# 可能遇到的问题

## CMake的安装

直通点：[戳这里](https://blog.csdn.net/sanqima/article/details/132634898?ops_request_misc=&request_id=&biz_id=102&utm_term=cmake%20windows&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-0-132634898.142^v100^pc_search_result_base7&spm=1018.2226.3001.4187)

# 配置

## 以SqList为例

- 进入SqList文件下的build目录

   ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20130505.png)
- 清空build

   ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20130543.png)
- 进入cmd

   ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20130554.png)

- 使用cmake编译
  
  ```
  cmake ..
  ```
 ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20131646.png)
  
- 打开SqList.sln

   ![]()
- 设置启动项

   ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20131738.png)
- 进行调试

   ![](https://github.com/369qwer/Data_Structure/blob/master/Sample%20Photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-19%20131819.png)
  

# 后续提交


## 步骤 1: 拉取远程仓库的更改

使用以下命令拉取远程仓库中的最新更改，并尝试自动合并到您的本地分支：
```
git pull origin master
```
这里假设您正在使用名为 origin 的远程仓库，且您的分支名为 master。这个命令会从 origin 拉取 master 分支的更改，并尝试将这些更改合并到您当前的本地分支。

## 步骤 2: 上传

```
git add .
git commit -m "A brief description of changes"
git push
```




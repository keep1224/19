   git


    三个区：
        工作区：写代码的地方==========武汉市有很多人
        暂存区：======    ===========去机场
        仓库区：=====================登机【飞机还没有起飞】


    仓库的演示
    1、初始化一个仓库====git  init  
    2、将代码提交到暂存区====git  add  文件路径  =====git  add  index.html || git  add  . ||  git  add  *
    3、将代码提交到仓库区====git  commit  -m  '这里写注释'

    4、git  checkout  index.html===切换到上一次的状态
    5、git  status  检测状态

    6、git   rm  --ached  删除的暂存区文件

    7、git  reset  --hard 版本id=====操作的是仓库区
    8、git   log======查看提交至仓库区的记录
        git  reflog===查看详细日志

        ================
        master====这个分支一般用于上线使用，所以大家不要操作他

    分支   
    9、git  branch    ========查看分支   
    10、git  branch   dev  ====创建分支【分支名自己定义】
    11、git checkout   dev=====切换分支 
        注释：切换分支时，必须先要让当前分支提交  add  +  commit 
    12、git  merge  分支名====合并两个分支
    13、git  branch  -d  分支名====删除分支

        这个了解====
            14、git  stash======这个是将文件剪切临时存储
            15、git  stash pop  ====将剪切的文件还原

    16、git  push  远程仓库地址  分支名 =====将本地仓库中的某个分支提交到远程仓库中 
    
            17、git   remote  add  别名  远程仓库地址  分支
            18、git  push  别名  分支
            19、git   push  -u  别名  分支
    20、git  push=====17-19都是为20做准备
    21、git  clone  远程仓库地址
    22、git  pull====拉去远程仓库中的文件
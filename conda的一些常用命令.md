1.创建一个新的环境
  conda create -n env_name python=3.6 (env_name即为环境的名字，如tensorflow）
2.查看所有创建的环境
  conda info -e
3.移除一个环境环境
  conda remove -n env_name --all
4.查看某个环境下有哪些包
  conda list -n env_name
5.给某个环境装包
  conda install -n env_name package_name=version
6.卸载某个环境的包
  conda remove -n env_name package_name
7.激活某个环境
  activate env_name
8.退出某个环境
  conda deavtivate
9.换回默认源
  conda config --remove-key channels
10.让终端打开不默认显示base
   通过将auto_activate_base参数设置为false实现：
   conda config --set auto_activate_base false
11.修改channels就是修改.condarc文件，直接把清华源官方的复制粘贴进去就行




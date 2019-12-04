dpkg -i package_name.deb   安装软件包
dpkg -r package_name       卸载已安装的软件包, 但不删除配置文件

dpkg -P  package_name     卸载已安装的软件包，同时删除配置文件

但是dpkg无法解决依赖问题，所以还是推荐使用Ubuntu软件管理程序来安装deb包
# VDHttpsTool
个人项目,基于AFNetWorking3.1.0的网络封装

    修改info.plist文件添加允许请求即从iOS起https相关
    请先让后台人员提供苹果承认机构颁发的证书，并转为cer格式的文件放入项目目录中，
    并修改.m文件中证书文件路径(位于单例方法中)
    别忘了配置baseURL:使用时请设置服务器基地址！！！

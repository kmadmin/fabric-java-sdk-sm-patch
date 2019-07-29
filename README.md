# fabric-java-sdk-sm-patch
the guomi patch for hyperledger fabric java sdk

使用步骤
1）下载fabric java sdk源码
 git clone –b v1.4.3 https://github.com/hyperledger/fabric-sdk-java.git
2）Eclipse 开发环境
可参照官方文档 https://github.com/hyperledger/fabric-sdk-java/blob/master/docs/EclipseSetup.md
3）应用国密补丁
在fabric-java-sdk目录下
git clone https://github.com/kmadmin/ fabric-java-sdk-sm-patch.git
git am fabric-java-sdk-sm-patch/fabric-java-sdk-sm-patch
eclips重新编译工程

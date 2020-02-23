#代理金小程序后端

后端框架目录：
kfzx-aga-parent:

        kfzx-aga-batch:
                  |--pom.xml:导入的依赖   

        pnmt-wx-service:

                  |--src

                            |--   main:

                                   |-- java:

                                       |--  com.kfzx 

                                            |--aga
                                                  |-- wx

                                                         |--bean：存放数据库表结构实体类

                                                         |--bussi：存放对应服务的复杂操作的BO

                                                         |--comm:

                                                                   |--constant:存放一些项目通用属性

                                                                   |--dict :存放一些公共枚举

                                                                   |--errormsg :存放错误实体类及公共错误属性值

                                                                   |--exception :存放一些自定义运行时异常

                                                                   |--handler :存放异常操作类

                                                                   |--interceptor :存放定义的全局拦截

                                                                   |--smsb :存放一些公共输入输出类

                                                                   |--utils :存放一些基础工具类

                                                                   |--VO :存放一些公共输入输出类

                                                                   |--MiniProgComm :存放公共事件编号

                                                                   |--PmmComm.java :存放公共事件编号

                                                         |--controller:存放Controller操作

                                                         |--impl ：存放Service的实现类

                                                         |--mapper：存放对数据操作的mapper类

                                                         |--repository：存放数据厂库层操作

                                                         |--ApplicationStart.java:启动文件

                                   |--resources:存放资源文件

                                       |--.........

                                   |--存放启动sh文件

                        |--  test:存放测试文件      

                                   |--java

                                       |--ControllerTset:存放控制Controller层测试脚本

                                       |--Mapper:存放直接查询数据库操作

                                       |--parameter:存放基础测试脚本

                                       |--serviceTest:存放service层测试脚本

                                       |--starter:存放启动类                              

                  |--target：存放编译过后的class文件

                  |--pom.xml:导入的依赖

        pnmt-wx-stub:

                  |--src

                            |--main

                                   |--java

                                       |--com.icbc.pnme.wx

                                           |--dicbase：存放一些获取枚举后者字典值得接口

                                           |--dto：存放中间类

                                           |--service：存放服务接口类

                                           |--vo:存放输入输出类

                  pom.xml:导入依赖

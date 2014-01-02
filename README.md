mvn_application4
================


4.假设我们有三个Project libA,libB,appC,其中appC包含主执行主程序（非web程序），libA,libB是两个library库Project，在appC的resouces中还包含conf/setting.xml cong/db-setting.xml, bin/startup.sh readme.txt等资源文件。
如何利用maven的build功能将这3个Project输出为一个可发布的标准结构（输出可部署的文件夹）。
  lib/
      liba.jar
      libb.jar
      appC.jar
  conf/
      setting.xml
      db-setting.xml
  bin/
      startup.sh
  readme.txt

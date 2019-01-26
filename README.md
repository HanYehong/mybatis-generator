# mybatis-generator
mybatis自动生成工具

1. 编辑generatorConfig文件：

  重要：修改【数据库名】【用户名】【密码】，以及需要生成的【数据库表名】

  可以改：（1）生成的包名，比如com.njit.xydl.car.entity为实体类生成后所处的包名，dao和mapper类似。（2）所有代码生成的位置，文件中默认为src，因此在根目录有一个src文件夹，若要改成其它，切记一定要在根目录创建对应名称的文件夹，不然会报“目标文件夹不存在”错误。

2. 保存编辑后的generatorConfig文件，并在当前目录下启动cmd命令界面

3. 在cmd命令行中输入以下命令（完全复制即可）：java -jar mybatis-generator-core-1.3.7.jar -configfile generatorConfig.xml -overwrite

4. 回车，等待运行成功，会提示successful

5. 在根目录的src文件夹中可以查看所有生成的代码

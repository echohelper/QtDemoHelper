简介：自定义式模板生成程序；可通过编辑配置和模板文件，一键生成目标工程。

1、xxxType类型：则是专门生成dll, lib, exe项目。

2、其他类型包含：基于产品项目工程模板类型、及自定义格式类型。

3、要保证配置文件字段在项目中的唯一性；支持配置的模板类型切换时的实时读取。

4、EveryBim中使用：Release, DRelea；SmartSim中使用：Relea, Drelea。

5、ini文件是自解析配置字段，会对值进行空格过滤、非变量名字符进行检查。自动跳过不符合命名。

6、对ini文件中的空格过滤规则：去除字符旁的所有空格。

7、[ProjectName]组中字段仅解析一个；[FileKey]组中字段解析数量无限制。

8、文件编码统一使用UTF-8。

9、配置文件的注释格式支持：//、#；其行其后内容被注释

10、配置文件字段应为必填项；若值为空，则删掉位置上的key。


注：SmartSim（即：4D）。

注：如果添加自定义格式模板，则只需创建一个类型目录，和配置类型目录中的config.ini文件。
（更多详细，请参考其他模板配置：DemoType）

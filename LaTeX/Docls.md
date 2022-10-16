# 文档结构
* \NeedsTeXFormat{LaTeX2e}[YYYY/MM/DD] 指明该文档类所需的$ \LaTeX $版本及其对应的日期
* ProvidesClass{name}[YYYY/MM/DD version description] 指明该文档类的name，且文件名必须与其一致；附加信息为该文档类的大致描述
* \RequirePackage[options]{package}[date] 引用其他的宏包
* \LoadClass[options]{class-name}[date] 加载其他的文档类
* \newcommand{\name}{code} 定义新命令name
* \newenvironment{name}{before}{after} 定义新环境
* \DeclareOption{option}{code} 定义选项，如果出现该option则执行代码code
* \ProcessOptions\relax 终止执行上述的选项，此两者一般成对出现

# 最小文档
文档必须包括四个内容：**\normalsize,\textwidth,\textheight,页数的规范**，称为最小文档。

# 参数传递
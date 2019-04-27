# PDLL
PDLL 即 Program Dynamic Loading Library，程序动态加载库，意在构建一个在MCU上实现动态加载程序的库，基于MCU无MMU，PDLL设计应直接加载 bin格式程序，同时提供统一API接口，仪确保同一个程序可以不用重新编译直接在同系列芯片或者同指令集芯片上运行。


    a.项目简介
    
    WordCount是一个命令行文本技术统计程序，做正确统计导入的纯英文txt文本中的字符数，行数，单词数，空行数。


    相关用法：
    
    将纯英文文本放在与可执行程序同一个文件夹里。
    命令模式：
    wc.exe -c显示文件的字符数、
    wc.exe -l行数、
    wc.exe -w单词、
    wc.exe-a空行数、代码行数、注释行数的统计测试
    注：file.txt需放在与wordcount.exe相同目录下。

    b.文件列表
    
    WordCount.cpp
    WordCount.exe
    reandme.md
    test用于存放测试文件file.txt


    c.例程运行
    
    test(1）
    
    wc.exe -c C:\Users\HAWER_\Desktop\NE.txt
    C:\Users\HAWER_\Desktop\NE.txt
    char count is ：19
    请按任意键继续. . .
    wc.exe -w C:\Users\HAWER_\Desktop\NE.txt
    word count is ：4.
    请按任意键继续. . .
    wc.exe -l C:\Users\HAWER_\Desktop\NE.txt
    line count is ：1.
    请按任意键继续. . .
    wc.exe -a C:\Users\HAWER_\Desktop\NE.txt
    code line count is ：1.
    empt line count is ：0.
    note line count is ：0.
    请按任意键继续. . .
    
    test（2）
    
    wc.exe -c C:\Users\HAWER_\Desktop\wca.txt
    C:\Users\HAWER_\Desktop\wca.txt
    char count is ：4896
    请按任意键继续. . .
    wc.exe -w C:\Users\HAWER_\Desktop\wca.txt    word count is ：453.
    请按任意键继续. . .
    wc.exe -l C:\Users\HAWER_\Desktop\wca.txt
    wc.exe -l C:\Users\HAWER_\Desktop\wca.txt
    line count is ：205.
    请按任意键继续. . .
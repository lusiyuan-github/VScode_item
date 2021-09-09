# VScode_item
用vscode编写各种语言的注意事项

## 0.总体

(1) 推荐插件：

​		Bracket Pair Colorizer

​		OneDark-Dark+

(2)注意事项：

 	1.vscode 的相对路径与其他编译器不同[vscode的相对路径 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/159435958)

## 1.编写 Verilog

(1) [用VSCode编辑verilog代码、iverilog编译、自动例化、自动补全、自动格式化等常用插件 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/338497672)

(2) 当编写tb文件报错时Unknown module type同样参考（1）

(3) 需要对代码编译进行报错显示需要安装

(3) 推荐插件：

​	 	Verilog-HDL/SystemVerilog/Bluespec SystemVerilog

​		 TerosHDL



## 2.编写java

(1) header参考格式：

```json
{
    "HEADER": {
        "prefix": "header",
        "body": [
            "/**",
            "@file         :$TM_FILENAME",            
            "@time         :$CURRENT_YEAR/$CURRENT_MONTH/$CURRENT_DATE $CURRENT_HOUR:$CURRENT_MINUTE:$CURRENT_SECOND",
            "@author       :Lusiyuan",
            "@Software     :VScode",
            "@usage        :",
            "*/",
            "$0"
        ],
    }
}
```

(2) 不推荐用code runner，会报错乱码

(3) 设置编译器用命令：Configure Java Runtime

​		直接使用底下的 Install A JDK ，必须选择JDK11不然无法编译

(4) 推荐插件：

​		Extension Pack for Java`v0.18.和拓展包




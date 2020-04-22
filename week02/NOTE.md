# 每周总结可以写在这里
# 作业1 #
    var reg1 = /^((0|[1-9]\d*)(\.\d*)?([eE][+-]?\d+)?|\.\d+([eE][+-]?\d+)?|0[bB][01]+|0[Oo][07]+|0[Xx][0-9a-f]+)$/gi;
    
# 作业2 #

    let str="这是测试,12.~~SAFAFsf";
    let utf8="";
    for(let i=0;i<str.length;i++){
       let codeNum= str.codePointAt(i);
       let hexadecimal=codeNum.toString(16);
       utf8+="\\u"+hexadecimal.padStart(4,0);
    
    }
    console.log(utf8);

# 作业3 #

	不太会

# 总结 #

![](https://szq-private-test.oss-cn-beijing.aliyuncs.com/%E5%89%8D%E7%AB%AF%E8%AE%AD%E7%BB%83%E8%90%A5/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.png)

之前一直不太了解正则，本周主要学习内容整理了一个思维导图，还需要多加练习。
ExHentaiReader

FORK 一下  
研究怎么自由更改标签

代码生成器
https://lhj5426.github.io/

修改标签方法 FORK 原始代码 
https://github.com/manakanemu/ExHentaiReader
然后修改标签文件 tag.json.js
修改完标签之后修改
修改tag.json.js 内的
TAGDICVERSION":1.版本号
修改Reader.js内 475 476 行
const version = 1.81
const currentTagDicVersion = 1.81
版本号
修改web文件夹内 Reader.js.test
\web\Reader.js.test

Reader.js.test 文件 
第474 475 行
const version = 1.81
const currentTagDicVersion = 1.81

保持这5个文件版本号一致 生成代码 手机端刷新就可以了
具体 在这里
https://github.com/manakanemu/ExHentaiReader/issues/10
![image](https://user-images.githubusercontent.com/30548000/114675418-ca24b780-9d3a-11eb-83b8-c4aec809c7d8.png)

我只弄了我自己的常用标签 

最后 感谢开发者 

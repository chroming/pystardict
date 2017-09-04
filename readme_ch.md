# pystardict 模块

## 基本用法

```python
from pystardict import Dictionary

dict = Dictionary('./dict/stardict-oald-cn-2.4.2/oald_cn')
print(dict0['test'])
```

## 安装

`pip install pystardict`

同时[在这里](http://download.huzheng.org/zh_CN/)下载你需要的词库文件。比如需要英中词典，可以下载`zh_CN(简体中文)--牛津高阶英汉双解`，下载之后解压出来即可。

## 使用

导入词典文件：

```python
from pystardict import Dictionary

# 此处./dict/stardict-oald-cn-2.4.2/ 词典文件的解压路径,oald_cn是词典文件名
dict0 = Dictionary('./dict/stardict-oald-cn-2.4.2/oald_cn')
```

获取单词test的翻译结果：

`print(dict0['test'])`


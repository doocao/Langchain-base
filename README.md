# Langchain-base

代码参考 LangChain-Chatchat项目
https://github.com/chatchat-space/Langchain-Chatchat

安装全部依赖

$ pip install -r requirements.txt

通常不能成功安装 zh_core_web_sm

比如在在知识库管理的时候报错
[E050] Can’t find model ‘en_core_web_sm’. It doesn’t seem to be a Python package or a valid path to a data directory.

方法一：在线安装zh_core_web_sm

$ python -m spacy download zh_core_web_sm

方法二：从GitHub上下载安装

$ pip3 install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.2.0/en_core_web_sm-3.2.0.tar.gz

方法三：终端pip安装whl

下载https://github.com/explosion/spacy-models/releases?q=zh_core_web_sm&expanded=true
得到文件zh_core_web_sm-3.6.0-py3-none-any.whl

$ pip install zh_core_web_sm-3.6.0-py3-none-any.whl
即可


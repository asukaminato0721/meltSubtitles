# Melt subtitles(融化字幕)

[只留字幕中的生词，并翻译](https://zhuanlan.zhihu.com/p/25854872)

## 安装和使用
0. 安装python 2.7.9 以上，推荐[python 3.5](https://www.python.org/downloads/release/python-353)
1. pip install -r requirements.txt 
2. python main.py zimu.srt -w 单词库

   单词库在文件夹wordsRepo, 如果不指定单词库，默认使用5000的。
   
   或者对多个字幕转换 python main.py *.srt -w ./wordsRepo/en5000x.csv

## 词库有[5000](http://www.wordfrequency.info/free.asp),[10000](https://github.com/first20hours/google-10000-english)


## To do 
1. [ ] 英文释义选择

2. [x] 批量转换

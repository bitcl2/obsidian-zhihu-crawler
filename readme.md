###感谢原作者https://github.com/Geralt-TYH/obsidian-zhihu-crawler

#2022.5.8 by-bitcl2
修改几个小bug
###1、收藏标题中含有/会被视为次级文件夹，备份过程中断
###2、知乎的新视频业务收藏后无法导出，原因是元素不一样，找不到元素导出失败。
###这个我还没来得及修复




# 项目介绍
该项目用于将知乎的收藏夹（公开）导出为markdown格式的文件，供学习和研究使用。

# 安装
首先安装python

然后安装依赖
```bash
pip install -r requirements.txt
```
# 使用
首先，请找到您想导出的收藏夹的 url
然后，在终端（cmd）界面下输入
```bash
python main.py [收藏夹的url]
```
等待下载完成
- markdown 文件将保存在该目录下的**剪藏**文件夹下，
- 文章中的图片将保存在剪藏文件夹中的**assets**文件夹中





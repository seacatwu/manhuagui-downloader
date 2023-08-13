# manhuagui-downloader 漫画柜下载器

TODO
下载界面增加滚动条，使之匹配特别多话的漫画下载。

**已解决** 因为exe文件太大，需要重新用pipenv削减文件体积。https://www.zhihu.com/question/281858271  

带有图形界面，纯py，点击exe文件可直接运行。

decoder.py中破解js那段参考自https://github.com/HSSLC/manhuagui-dlr 中的trans.py和parse.py。版权归HSSLC所有。

1.复制漫画网址，包含comic/xxxx 就可以了，点击download
![image](https://github.com/XiangxinKong/manhuagui-downloader/blob/master/screenshot/0.GIF)

2.勾选要下载的章节。灰色的是已经下载过的。
![image](https://github.com/XiangxinKong/manhuagui-downloader/blob/master/screenshot/1.GIF)

3.开始下载。下载完后会自动转码成jpg。（目前设置每0.1秒下载1页，如果下载量不是很大，可以调快）
![image](https://github.com/XiangxinKong/manhuagui-downloader/blob/master/screenshot/2.GIF)

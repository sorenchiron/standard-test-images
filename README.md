# standard-test-images
图像类标准测试集（images used for various processing testings）

# List of contents
- Five representative test images: [link](5-test-images/readme.md)
- The Miscellaneous volume [link](http://sipi.usc.edu/database/database.php?volume=misc&image=15#top)
    - see: [preview](misc/readme.md)
- Greyscale set and colour set [link](http://links.uwaterloo.ca/Repository.html)
- Public-Domain Test Images for Homeworks and Projects [link](https://homepages.cae.wisc.edu/~ece533/images/)
- Kodak: [link](http://r0k.us/graphics/kodak/) and [link](http://www.cs.albany.edu/~xypan/research/snr/Kodak.html)
- BSD500: [berkeley](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html)
- set5 and set14: [kaggle](https://www.kaggle.com/ll01dm/set-5-14-super-resolution-dataset?select=Set14)
- Twitter 40 images
    - more twitter datasets: [github](https://github.com/shaypal5/awesome-twitter-data)
    
## 下载部分数据

1. 选择目标文件夹或者文件，比如：`https://github.com/sorenchiron/standard-test-images/tree/main/Set14`
2. 转化为SVN地址
    - 将 `tree/main` 更改为 `trunk`
    - 得到：`https://github.com/sorenchiron/standard-test-images/trunk/Set14`
3. 使用svn下载：`svn checkout https://github.com/sorenchiron/standard-test-images/trunk/Set14`

#### 特别提醒：

Github可能需要半分钟的时间转化地址，所以请耐心等待下载
You might not see any activity immediately because Github takes up to 30 seconds to convert larger repositories, so be patient.

[reference](https://stackoverflow.com/questions/7106012/download-a-single-folder-or-directory-from-a-github-repo)

## 注意事项

如果浏览器没有展示图像预览，则说明markdown转化暂无法支持tiff格式图像，请直接到目录中下载原始图片
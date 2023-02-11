最终达到86的miou与90的map；使用pspnet；数据集使用老鼠肾小球；  
模型链接如下：  
链接：https://pan.baidu.com/s/1h4aH8f7fk0wFX_y8rmkl6A  
提取码：rafj  
--来自百度网盘超级会员V2的分享  
  
最终版本使用的是和范例代码中相同的模型，在自己使用mmsegmentation 的 main 分支进行尝试时，发现和范例代码（后来发觉范例代码使用的是dev-1版本的mmseg）有着很大的区别，例如dataloader部分，在main分支中（main中使用的是datadict（train，val...））并不是使用这样的代码来完成数据集读入的，虽然其他部分可以理解与修改，最终问题出在了数据集读取上，main分支中的数据集读取需要按照文件夹划分好，但是范例代码与数据集划分方式是全部存入一个文件夹，靠.txt文件来分割数据集；  

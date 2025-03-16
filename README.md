# YureVita-CHS
YumeustsutsuRe CH Patches

![img](https://yuremaster.kogado.com/wp-content/themes/yurimas/img/logo2.png)

本项目是为PSVita上的《梦现Re:Master》与《梦现Re:After》移植的汉化补丁，汉化文本均来自Nintendo Switch

项目&美工&移植：LittleFIve
## 本项目已于2023/11/14在PSVita破解吧正式发布！本仓库为归档
发布链接：

简中 [https://tieba.baidu.com/p/8719217246](https://tieba.baidu.com/p/8719217246)

繁中Mas [https://tieba.baidu.com/p/8475333282](https://tieba.baidu.com/p/8475333282)

繁中AF [https://tieba.baidu.com/p/8477146705](https://tieba.baidu.com/p/8477146705)
# Build (Windows)
0.提取Nintendo Switch版的视频并压缩至960x544分辨率

1.克隆或下载本库

2.打开MakeReMaster或者MakeAfter

3.执行``make.bat``脚本，将会生成res_jp.psarc文件
# Install Guide
> （仅简体中文补丁需要安装插件更改字库）
>
>1.下载[sa0tour0](https://github.com/SKGleba/VitaTools/blob/main/sa0tour0/build/sa0tour0.skprx)并安装该插件
>
>2.使用vitashell将``sa0``中的所有文件放入``ur0:data``文件夹

1.首先安装好[repatch](https://github.com/SonicMastr/rePatch-reLoaded/releases/tag/v2.0)插件

2.在PSVita存储卡根目录(``ux0``)创建``repatch/[TITLEID]/``

3.将做好的视频放入``repatch/[TITLEID]/mov/``，然后将res_jp.psarc放入``repatch/[TITLEID]/``文件夹

- ReMaster的TID为PCSG01266
- ReAfter的TID为PCSG01317

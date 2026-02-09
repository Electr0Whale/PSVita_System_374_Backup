该Release可解决C3-3822-5报错，适用于日版PSV2000。
其他区域机型需要自行寻找索尼官方发布的psp2-updatelist.xml文件，从xml文件中的链接下载三个PSP2UPDAT.PUP文件并自行加上数字后缀以防止重复，最后将xml文件中的对应链接也加上数字后缀，QCMA记得**不要勾选**Ignore local file psp2-updatelist.xml on update folder

转自[PSV救砖图文教程](https://shipengliang.com/games/psv%e6%95%91%e7%a0%96%e5%9b%be%e6%96%87%e6%95%99%e7%a8%8b.html "PSV救砖图文教程")，经过部分截取和修改

作者：时鹏亮 | 更新时间：07/05/2024 06:00:13

通过QCMA进行救砖，操作如下：

1.  下载并安装QCMA：[Qcma_setup-0.4.1.exe](https://github.com/codestation/qcma/releases/download/v0.4.1/Qcma_setup-0.4.1.exe "Qcma_setup-0.4.1.exe")
2.  将[PSV374JP.7z](https://github.com/Electr0Whale/PSVita_System_374_Backup/releases/download/backup/PSV374JP.7z "PSV374JP.7z")下载好，将解压后的所有文件拷贝进QCMA中的PSV update文件夹  
3.  修改QCMA other选项中的配置如图（因为这里用的是3.74固件，所以version为03.740.000
[![QCMA Settings](https://github.com/Electr0Whale/PSVita_System_374_Backup/blob/main/QCMA%20Settings.png "QCMA Settings")](https://github.com/Electr0Whale/PSVita_System_374_Backup/blob/main/QCMA%20Settings.png "QCMA Settings")
4.  PSV进入安全模式，选升级系统软件  
5.  连接至电脑进行升级  
6.  系统会自动识别到升级文件，点继续  
7.  PSV即可升级变回3.74系统。  

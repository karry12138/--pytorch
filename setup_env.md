# 写在前面
这个是nvidia驱动，cuda安装，pytorch导入的环境配置。
整体逻辑为：pytorch安装依赖于cuda版本，cuda版本依赖于nvidia驱动版本。
所以要先从nvidia驱动搞起。
配置anaconda的内容将不再赘述。

截至230405，pytorch的最新cuda版本为11.8，只要你的cuda版本大于11.8就行
https://pytorch.org/get-started/locally/

# 1 安装cuda
## 装最新版本的nvidia驱动
如果你电脑上装过GeForce Experience，可以直接在这里面装。
如果没有，https://www.nvidia.cn/Download 可以自动搜索得到你电脑配置的最新驱动的安装包。
安装完后，
在cmd中输入`nvidia-smi`可以查看你电脑的nvidia驱动版本以及该版本支持的cuda版本

<details>
  <summary>如果你要安装指定版本的cuda与nvidia驱动</summary>

### 确定本机配置
GEForce RTX 3060 laptop
  
 
</details>
 
## 装配套的cuda
https://developer.nvidia.com/cuda-toolkit-archive
直接下载。

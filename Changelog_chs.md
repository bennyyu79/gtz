### gtz-1.2.3 [2019/01/24]

主要修改如下：

1、提高了压缩gz文件和解压成gz文件的性能

2、解决gtz不能运行在某些特定CPU型号的服务器上的问题

3、修正压缩gz格式文件时进度条显示超过100%的问题

4、新增 -s 参数，用于压缩时开启物种自动识别功能，该参数在-b指定了bin文件时会失效

5、新增 --bin-path 参数，用于开启物种自动识别时，指定bin文件所在目录。如果没有修改bin默认路径（～/.config/gtz），则可以不指定


### gtz-1.2.2 [2018/11/09]

主要优化索引文件的加载速度，压缩速度会有明显的提升


### gtz-1.2.1 [2018/10/30]

1、解决压缩完成后做校验时，gtz有时会比较慢的问题

２、解决用-c做解压时，-e不工作的问题


### gtz-1.2 [2018/10/25]

１、解决GTZ有时加载慢的问题

２、解决输入ctrl+c，gtz有时不能退出的问题


### gtz-1.1 [2018/10/16]

增加功能:

１、-c/--stdout 解压到终端

２、-z/--fastq-to-fastq-gz 将fastq解压成gz格式，该选项只对fastq有效，非fastq会忽略该选项


### gtz-1.0 [2018/10/11]

基础修订

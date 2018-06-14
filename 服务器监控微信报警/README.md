**补充说明**

jq 是一款命令行下处理 JSON 数据的工具。其可以接受标准输入，命令管道或者文件中的 JSON 数据，经过一系列的过滤器(filters)和表达式的转后形成我们需要的数据结构并将结果输出到标准输出中。jq 的这种特性使我们可以很容易地在 Shell 脚本中调用它。

安装jq
```bash
git clone https://github.com/stedolan/jq.git
cd jq
autoreconf -i
./configure --disable-maintainer-mode
make
sudo make install
```

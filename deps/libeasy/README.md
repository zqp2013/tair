#如果./configure后没有生成Makefile文件，查看config.log具体错误

/usr/bin/ld: cannot find -lssl   解决方法
apt-get install libssl-dev
验证：gcc -lssl --verbose

#如果./configure后没有生成Makefile文件，查看config.log具体错误

/usr/bin/ld: cannot find -lssl   解决方法
apt-get install libssl-dev
验证：gcc -lssl --verbose


>>> 由于libssl版本兼容问题，有编译警告，而.ac文件中-Werror会将警告当错误，已经改成-Wno-error

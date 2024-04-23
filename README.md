# 如何编译
根据开发板不同的SDK使用对应路径下的交叉编译器
## 第一步设置临时环境变量
export CROSS_COMPILE=/mnt/disk/dev2/luckfox-pico/tools/linux/toolchain/arm-rockchip830-linux-uclibcgnueabihf/bin/arm-rockchip830-linux-uclibcgnueabihf-

这里的路径是你的交叉编译器路径

## 执行编译
make

# 使用
将可执行文件（没有后缀的）复制到开发板上

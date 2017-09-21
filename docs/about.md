
## 经常用到的命令
1. mount  //192.168.0.25/linuxsir /mnt/linuxShare/
2. git pull --rebase origin master
3. 安装docker docker命令
4. 安装gocode
5. 端口号9091-9099



## 安装markdown写作环境
1. 先安装docker 环境命令为  curl -sSL https://get.daocloud.io/docker | sh
2. 下载 docker 虚拟机 git clone https://github.com/visint/myDocker
3. 进入 /myDocker/jybseconddocker/business# make
4. 修改Makefile 文件 run 命令下的 mnt目录对应的目录/home/jiang/
5. 在目录/home/jiang/ 下运行 git clone https://github.com/visint/markdown  
                            git clone https://github.com/visint/liveing
6. 修改了markdown 里面的文件需要生成新的文档命令 docker exec -it business /mnt/markdown/build.sh,docker exec -it business /mnt/liveing/build.sh                             

## 为开源做贡献
 * 加入图片 ![name](images/name.png)
 * 加入链接[https://coding.net/u/openwrtio](https://coding.net/u/openwrtio)

## 感谢

 * 感谢 [gentleface.com](http://www.gentleface.com/) 提供logo设计。
 * 感谢 [daocloud.io](https://account.daocloud.io/signup?invite_code=c8bkkhc1uq8i7z8nin93) 提供免费容器和主机。

<!-- 多说评论框 start -->
<div class="ds-thread" data-thread-key="about" data-title="关于我们" data-url="http://openwrt.io/about/"></div>
<!-- 多说评论框 end -->

# Trojansh
Trojan分解自动安装脚本

==========================================================

支持：centos7+/debian9+/ubuntu16.04+

网站：www.v2rayssr.com （已开启禁止国内访问）

YouTube频道：波仔分享

==========================================================

本Trojan安装代码 www.v2rayssr.com 首发

【https://www.v2rayssr.com/trojan-2.html 根据网站内容完整补充】
1、检查 SELinux 是否为关闭状态
一般情况下，VPS 的 SELinux 处于关闭状态，但是不排除所有，大家检查一下！
/usr/sbin/sestatus -v      ##如果返回参数为 enabled 即为开启，disabled 为关闭(Bebian默认关闭)
若是开启状态，如何关闭 SELinux 服务？
修改 /etc/selinux/config 文件，将 SELINUX=enforcing 改为 SELINUX=disabled，重启 VPS 以后 SELinux 即为关闭状态。


为了适合新手小伙伴，本代码分解三部分，每个部分根据代码回显提示进行对应操作：

{安装BBRPLUS加速}
wget -N --no-check-certificate "https://github.com/ylx2016/Linux-NetSpeed/releases/download/sh/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

1. wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan1.sh" && chmod +x trojan1.sh && ./trojan1.sh

2. wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan2.sh" && chmod +x trojan2.sh && ./trojan2.sh

3. wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan3.sh" && chmod +x trojan3.sh && ./trojan3.sh

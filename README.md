# Remember
Notes

Some questions about install Theano under Ubuntu16 (Virtual Machine).

First sudo apt-get update failed:

Reading package lists... Done
E: Problem executing scripts APT::Update::Post-Invoke-Success
'if /usr/bin/test -w /var/cache/app-info -a -e /usr/bin/appstreamcli;
 then appstreamcli refresh > /dev/null;
 fi'
E: Sub-process returned an error code

sudo pkill -KILL appstreamcli
wget -P /tmp https://launchpad.net/ubuntu/+archive/primary/+files/appstream_0.9.4-1ubuntu1_amd64.deb https://launchpad.net/ubuntu/+archive/primary/+files/libappstream3_0.9.4-1ubuntu1_amd64.deb
sudo dpkg -i /tmp/appstream_0.9.4-1ubuntu1_amd64.deb /tmp/libappstream3_0.9.4-1ubuntu1_amd64.deb

======================================================================================================
Second install Theano
http://blog.sina.com.cn/s/blog_75c0df1c0102xdt9.html
https://blog.csdn.net/jiandanjinxin/article/details/51954179
https://blog.csdn.net/xuezhisdc/article/details/47065475

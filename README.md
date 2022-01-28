

### find them

debian/ubuntu: 
 `cat /etc/apt/sources.list /etc/apt/sources.list.d/docker.list |grep deb |grep http|sed 's~.\+://~~g'|cut -d"/" -f1|sort -u`

# Nagios XI
Nagios XI�� Container ���·� �����ϱ� ���� ��������ϴ�.

##### - ����
```sh
[root@ruo91 ~]# docker build --rm -t nagios:xi https://github.com/ruo91/docker-nagiosxi.git
[root@ruo91 ~]# docker run -d --name="nagiosxi" -h "nagiosxi" \
-p 80:80 -p 443:443 -p 5666:5666 -p 5667:5667 nagios:xi
```

#### - WEB UI
![Nagios XI][1]

[1]: http://cdn.yongbok.net/ruo91/img/nagios/nagiosxi.png
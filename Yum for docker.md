## Docker Installation Guid : how we can install docker in the redhat 8 vm
1.  Configure yum for Docker for this first  Create a file "/etc/yum.repos.d/docker.repo"
Example:-
```
gedit /etc/yum.repos.d/docker.repo
[docker]
baseurl=https://download.docker.com/linux/centos/7/x86_64/stable/
gpgcheck=0
```

After this verify by "yum repolist" . You see some more software
2. Install Docker and start service : Run three command given belo
   1.  yum install docker-ce  --nobest
   2.  systemctl start docker
   3.  systemctl enable docker
   
Now successfully docker installed and verify by "docker info". I hope this will help you ...

![image](https://user-images.githubusercontent.com/49730521/119997038-ed56ae00-bfec-11eb-95d4-36db6ef2f10a.png)

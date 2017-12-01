
## Create Users ##

### ec2-user@ip-172-31-38-248 ###

*[ec2-user@ip-172-31-38-248 ~]$* **sudo useradd -u 2800 saturn**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo useradd -u 2900 haley**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo groupadd comets**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo groupadd planets**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo usermod -a -G comets haley**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo usermod -a -G planets saturn**

*[ec2-user@ip-172-31-38-248 ~]$* **sudo cat /etc/passwd | grep saturn**

	saturn:x:2800:2800::/home/saturn:/bin/bash

*[ec2-user@ip-172-31-38-248 ~]$* **sudo cat /etc/passwd | grep haley**

	haley:x:2900:2900::/home/haley:/bin/bash

*[ec2-user@ip-172-31-38-248 ~]$* **id saturn**

	uid=2800(saturn) gid=2800(saturn) groups=2800(saturn),2902(planets)

*[ec2-user@ip-172-31-38-248 ~]$* **id haley**

	uid=2900(haley) gid=2900(haley) groups=2900(haley),2901(comets)

*[ec2-user@ip-172-31-38-248 ~]$*


### ec2-user@ip-172-31-38-238 ###

[ec2-user@ip-172-31-38-238 ~]$ **sudo useradd -u 2800 saturn**

[ec2-user@ip-172-31-38-238 ~]$ **sudo useradd -u 2900 haley**

[ec2-user@ip-172-31-38-238 ~]$

[ec2-user@ip-172-31-38-238 ~]$ **sudo groupadd comets**

[ec2-user@ip-172-31-38-238 ~]$ **sudo groupadd planets**

[ec2-user@ip-172-31-38-238 ~]$

[ec2-user@ip-172-31-38-238 ~]$ **sudo usermod -a -G comets haley**

[ec2-user@ip-172-31-38-238 ~]$ **sudo usermod -a -G planets saturn**

[ec2-user@ip-172-31-38-238 ~]$

[ec2-user@ip-172-31-38-238 ~]$ **sudo cat /etc/passwd | grep saturn**

	saturn:x:2800:2800::/home/saturn:/bin/bash

[ec2-user@ip-172-31-38-238 ~]$ **sudo cat /etc/passwd | grep haley**

	haley:x:2900:2900::/home/haley:/bin/bash

[ec2-user@ip-172-31-38-238 ~]$

[ec2-user@ip-172-31-38-238 ~]$ **id saturn**

	uid=2800(saturn) gid=2800(saturn) groups=2800(saturn),2902(planets)

[ec2-user@ip-172-31-38-238 ~]$ **id haley**

	uid=2900(haley) gid=2900(haley) groups=2900(haley),2901(comets)

[ec2-user@ip-172-31-38-238 ~]$


### ec2-user@ip-172-31-43-67 ###

[ec2-user@ip-172-31-43-67 ~]$ **sudo useradd -u 2800 saturn**

[ec2-user@ip-172-31-43-67 ~]$ **sudo useradd -u 2900 haley**

[ec2-user@ip-172-31-43-67 ~]$

[ec2-user@ip-172-31-43-67 ~]$ **sudo groupadd comets**

[ec2-user@ip-172-31-43-67 ~]$ **sudo groupadd planets**

[ec2-user@ip-172-31-43-67 ~]$

[ec2-user@ip-172-31-43-67 ~]$ **sudo usermod -a -G comets haley**

[ec2-user@ip-172-31-43-67 ~]$ **sudo usermod -a -G planets saturn**

[ec2-user@ip-172-31-43-67 ~]$

[ec2-user@ip-172-31-43-67 ~]$ **sudo cat /etc/passwd | grep saturn**

	saturn:x:2800:2800::/home/saturn:/bin/bash

[ec2-user@ip-172-31-43-67 ~]$ **sudo cat /etc/passwd | grep haley**

	haley:x:2900:2900::/home/haley:/bin/bash

[ec2-user@ip-172-31-43-67 ~]$

[ec2-user@ip-172-31-43-67 ~]$ **id saturn**

	uid=2800(saturn) gid=2800(saturn) groups=2800(saturn),2902(planets)

[ec2-user@ip-172-31-43-67 ~]$ **id haley**

	uid=2900(haley) gid=2900(haley) groups=2900(haley),2901(comets)

[ec2-user@ip-172-31-43-67 ~]$


### ec2-user@ip-172-31-35-37 ###

[ec2-user@ip-172-31-35-37 ~]$ **sudo useradd -u 2800 saturn**

[ec2-user@ip-172-31-35-37 ~]$ **sudo useradd -u 2900 haley**

[ec2-user@ip-172-31-35-37 ~]$

[ec2-user@ip-172-31-35-37 ~]$ **sudo groupadd comets**

[ec2-user@ip-172-31-35-37 ~]$ **sudo groupadd planets**

[ec2-user@ip-172-31-35-37 ~]$

[ec2-user@ip-172-31-35-37 ~]$ **sudo usermod -a -G comets haley**

[ec2-user@ip-172-31-35-37 ~]$ **sudo usermod -a -G planets saturn**

[ec2-user@ip-172-31-35-37 ~]$

[ec2-user@ip-172-31-35-37 ~]$ **sudo cat /etc/passwd | grep saturn**

	saturn:x:2800:2800::/home/saturn:/bin/bash

[ec2-user@ip-172-31-35-37 ~]$ **sudo cat /etc/passwd | grep haley**

	haley:x:2900:2900::/home/haley:/bin/bash

[ec2-user@ip-172-31-35-37 ~]$

[ec2-user@ip-172-31-35-37 ~]$ **id saturn**

	uid=2800(saturn) gid=2800(saturn) groups=2800(saturn),2902(planets)

[ec2-user@ip-172-31-35-37 ~]$ **id haley**

	uid=2900(haley) gid=2900(haley) groups=2900(haley),2901(comets)

[ec2-user@ip-172-31-35-37 ~]$

### Cloud provider###
	AWS

### Linux release ###
	Red Hat Enterprise Linux 7.4

### Instances by IP address and DNS name ###
	54.201.188.54	ec2-54-201-188-54.us-west-2.compute.amazonaws.com
	52.303.143.167	ec2-54-202-143-167.us-west-2.compute.amazonaws.com
	54.186.62.122	ec2-54-186-62-122.us-west-2.compute.amazonaws.com
	34.214.222.244	ec2-34-214-222-244.us-west-2.compute.amazonaws.com

### file system capacity for the first node ###
	NAME    MAJ:MIN RM SIZE RO TYPE MOUNTPOINT
	xvda    202:0    0  80G  0 disk
	+-xvda1 202:1    0   1M  0 part
	+-xvda2 202:2    0  80G  0 part /
	xvdb    202:16   0  80G  0 disk
	xvdc    202:32   0  80G  0 disk

### The command and output for yum repolist enabled ###
*[ec2-user@ip-172-31-38-248 ~]$* **sudo yum repolist enabled**

	Loaded plugins: amazon-id, rhui-lb, search-disabled-repos
	https://rhui2-cds02.us-west-2.aws.ce.redhat.com/pulp/repos//rhui-client-config/rhel/server/7/x86_64/os/repodata/repomd.xml: [Errno 14] HTTPS Error 401 - Unauthorized
	Trying other mirror.
	rhui-REGION-client-config-server-7                                                                                                                                    | 2.9 kB  00:00:00
	rhui-REGION-rhel-server-releases                                                                                                                                      | 3.5 kB  00:00:00
	rhui-REGION-rhel-server-rh-common                                                                                                                                     | 3.8 kB  00:00:00
	(1/7): rhui-REGION-client-config-server-7/x86_64/primary_db                                                                                                           | 6.6 kB  00:00:00
	(2/7): rhui-REGION-rhel-server-releases/7Server/x86_64/group                                                                                                          | 709 kB  00:00:00
	(3/7): rhui-REGION-rhel-server-releases/7Server/x86_64/updateinfo                                                                                                     | 2.4 MB  00:00:00
	(4/7): rhui-REGION-rhel-server-rh-common/7Server/x86_64/updateinfo                                                                                                    |  32 kB  00:00:00
	(5/7): rhui-REGION-rhel-server-rh-common/7Server/x86_64/group                                                                                                         |  104 B  00:00:00
	(6/7): rhui-REGION-rhel-server-rh-common/7Server/x86_64/primary_db                                                                                                    | 119 kB  00:00:00
	(7/7): rhui-REGION-rhel-server-releases/7Server/x86_64/primary_db                                                                                                     |  44 MB  00:00:00
	repo id                                                                             repo name                                                                                          status
	rhui-REGION-client-config-server-7/x86_64                                           Red Hat Update Infrastructure 2.0 Client Configuration Server 7                                         8
	rhui-REGION-rhel-server-releases/7Server/x86_64                                     Red Hat Enterprise Linux Server 7 (RPMs)                                                           17,521
	rhui-REGION-rhel-server-rh-common/7Server/x86_64                                    Red Hat Enterprise Linux Server 7 RH Common (RPMs)                                                    228
	repolist: 17,757

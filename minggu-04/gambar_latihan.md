1. $ sudo useradd -s /bin/bash -d /opt/stack -m stack
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/01.PNG)

2. Add Stack User (optional) :
$ echo "stack ALL=(ALL) NOPASSWD: ALL" | sudo tee /etc/sudoers.d/stack
$ sudo su - stack
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/02.PNG)

3. Download DevStack : 
$ git clone https://opendev.org/openstack/devstack
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/03.PNG)

4. Repo devstack berisi skrip yang menginstal OpenStack dan templat untuk file konfigurasi :
$ cd devstack
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/04.PNG)

5. Memulai install :
$ ./stack.sh
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/05.PNG)
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/06.PNG)
![](https://github.com/mayamonika998/tekn-cloud-computing/blob/master/minggu-04/07.PNG)
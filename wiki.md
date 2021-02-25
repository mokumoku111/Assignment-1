
## ขั้นตอนการติดตั้ง **Jenkins**


### ขั้นตอนที่ 1 
ทำการดาวน์โหลด **Jenkins** จาก https://www.jenkins.io/download/
โดยเลือก **Download Jenkins version for : Windows** (ในกรณีที่ใช้ระบบปฏิบัติการ Windows)
	
<img src="Assignment-1/image_jenkins/jenkins_download.png" width = "800"/>
	
(ในที่นี้ใช้ version 2.281)

	> หากในเครื่องไม่มี JRE ต้องทำการติดตั้ง JRE ก่อน โดยสามารถดูได้จาก cmd และพิมพ์ java
	> โดยสามารถดาวน์โหลดได้จาก https://www.oracle.com/java/technologies/javase-jre8-downloads.html
	> เมื่อติดตั้งเสร็จแล้วให้ทำการ **PATH** ที่อยู่ของ Java แล้วรีสตาร์ทเครื่อง
	
<img src="image_jenkins/install_jre.png" width = "800"/>
	
### ขั้นตอนที่ 2
เมื่อทำการดาวน์โหลดเสร็จแล้วให้ทำการติดตั้ง 

<img src="image_jenkins/jenkins_install.png" width = "600"/>

<img src="image_jenkins/jenkins_install_2.png" width = "600"/>
เลือกที่อยู่ที่จะติดตั้ง จากนั้นกด **Next**

<img src="image_jenkins/jenkins_install_3.png" width = "600"/>

<img src="image_jenkins/jenkins_install_4.png" width = "600"/>
กด **testport** จากนั้นกด **Next**
	> Start port default ของ Jenkins จะใช้ :8080 หากในเครื่องมีเครื่องมืออื่นที่ใช้ port:8080 อยู่ Jenkins จะไม่ทำงาน

<img src="image_jenkins/jenkins_install_4.png" width = "600"/>
	
<img src="image_jenkins/jenkins_install_5.png" width = "600"/>

<img src="image_jenkins/jenkins_install_6.png" width = "600"/>
	
<img src="image_jenkins/jenkins_install_7.png" width = "600"/>
	
<img src="image_jenkins/jenkins_install_8.png" width = "600"/>

<img src="image_jenkins/jenkins_install_finish.png" width = "600"/>
เมื่อติดตั้งเสร็จแล้วให้กด Finish จากนั้นจะมีเว็บขึ้นมา 

<img src="image_jenkins/jenkins_alertPage.png" width = "600"/>
จากนั้นให้นำ Password ที่ได้จาก PATH สีแดงมากรอก

<img src="image_jenkins/jenkins_CreateUser.png" width = "600"/>
เมื่อกรอก Password แล้วจะให้สร้าง User Admin ให้ทำการ Create User เมื่อเสร็จแล้วกด Save and Continue

เมื่อสร้าง user admin สำเร็จ ให้ทำการ login เป็นการเสร็จสิ้นการติดตั้ง Jenkins
<img src="image_jenkins/jenkins_success.png" width = "600"/>










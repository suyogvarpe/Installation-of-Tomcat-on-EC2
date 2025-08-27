# Installation-of-Tomcat-on-EC2
Full project to installation of Tomcat on EC2 instance.


1)Create EC2 instance using port 8080 allowed.
2)Connect Ec2 instance using Root account.
3)Install Java on Ec2 instance using following command.
  #sudo yum install java-17-amazon-corretto -y 
4)Confirm and Check Java Version using following command which is installed by you.
  #java -version
5)Donwload Tomcat version using following command and it will be donwload in tar file.
  #wget https://archive.apache.org/dist/tomcat/tomcat-10/v10.1.28/bin/apache-tomcat-10.1.28.tar.gz
6)Extract this tar file using following command.
  #tar -xvzf apache-tomcat-10.1.28.tar.gz
7)Move apache tomcat into Tomcat folder.
  #mv apache-tomcat-10.1.28 tomcat
8)Change directory into Bin
  #cd tomcat/bin
9)Start tomcat using following command.
  #./startup.sh
10)Once installation complete kindly check tomcat installation done properly or not.
   Type following url by using Ec2 Public Ip in browser.
  http://<your-ec2-public-ip>:8080
  This URl should refelcted to Apache tomcat detailes page on this page it will shows tomcat installation succesfully done with installed tomcat version.
11)
  


  

  



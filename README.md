
# Creator is TCAT Dev Team#
## This Document describes How to create image and run the image code into Docker Environment and provide step by Step Screen about how to use tool ##

### How to create Docker Image the code into Docker ### 

1. __Go to Command Prompt__
2. __Change directory to the Folder where Src folder, Dockerfile, requirements.txt is Kept__
3. __Execute command: sudo docker build -t tcat-dcr-app .__
4. __Validate if the Image is craeted by running command: sudo docker images__
5. __To run image execute command: sudo docker run -d -p port:port tcat-dcr-app__
6. __Check if image is running by executing command: sudo docker ps --filter "name=image name"__


### How to access the tool ###
1. __In web browser go to the ip:port/login url. ip and port are as provided by docker during runtime__
2. __Enter Anthem EUMID for User__ 
  ![](pics/Login.png?raw=true)
3. __Enter Source system Database Details__
 ![](pics/SelectSource.png?raw=true)
4. __Enter Destination Database Type__
 ![](pics/DestDB.png?raw=true)
5. __Browse the standard Mapping document and upload__
 ![](pics/Browsefile.png?raw=true)
6. __Upload the Document to generate Test Cases__
![](pics/clickupload.png?raw=true)
7. __After Test Case Document is created a Page will appear to download the test Scripts as Excel into user's machine__
![](pics/DownloadPage.png?raw=true)
8. __Download the file__
![](pics/Downloadfile.png?raw=true)
9. __To check logfile to analyze error use the link given in pages to download Log files__
![](pics/DownloadLogLink.png?raw=true)
10. __Clicking the link will show available logs and allows to download it__
![](pics/downloadlog.png?raw=true)
 

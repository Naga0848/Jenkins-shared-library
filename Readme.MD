## this repo will have the Jenkins shared library related files for different programing languages



## Understanding Jenkinsfile and its corresponding Jenkins-shared-library structures

    - mana repo lo unde jenkinsfile poi jenkins-shared-library ni call chesthadi i.e., manam oka function ni call chesthunnam
    - mana repo lo unde jenkinsfile evaithe variables ni use chesthunnamo liike project, component etc... avve variables ni jenkins-shared-library lo env variables laga declare cheyali...so that avvi match aina tharvatha jenkins-shared-library will be triggered from our jenkinsfile

![alt text](images/shared-lib.png)

    - from the above image we can understand that line nos 10 and 11 are being called from the jenkinsfile which is in our repo as shown below

![alt text](images/jenkinsfile.png)    
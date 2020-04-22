# DingTalk-Dev (English)
This repository is based from two repos on DingTalk QuickStart (https://ding-doc.dingtalk.com/doc#/personnal/ekyhmf)
1. Applet Server Code

    `git clone https://github.com/open-dingtalk/eapp-personal-quick-start.git`
2. Applet Frontend Code

    `git clone https://github.com/opendingtalk/eapp-personal-quick-start-fe.git`


#### Pre Requisite:
1. DingTalk Admin Account and working Organization
2. Create Application thru DingTalk Admin Panel (https://open-dev.dingtalk.com/#/corpeapp)

    `Chinese-English Documentation` to `Mini Program Studio` (April 2020):

        In-House Development => Biz Program
        Third Party Personal => Personal Program 

3. Java JDK (Preferably Java 8), Maven, NPM

#### Steps:
On `back-end\` directory, do the following:

1. Modify the configuration `.\src\main\java\com\config\Constant.java` to replace `APP_ID` and `APP_SECRET` based from https://ding-doc.dingtalk.com/doc#/personnal/ekyhmf

2. Package the app

    `mvn clean package`

3. Run the app

    `java -jar  target/eapp-personal-quick-start-1.0.0.jar`

4. Verify if back-end is running properly  at `http://localhost:8080/welcome` 


On `front-end\` directory, do the following:

1. Using Mini Progam Studio, open the folder front-end\

2. Login to DingTalk and you should be able to compile the codes without issues.


For chatbot service:

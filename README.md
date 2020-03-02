# docdoku-plm-convert-all
only for deploy

1、导入convert 相关：  
```
mv  docdoku-plm-convert-all/*.ear ./glassfish/domains/domain1/autodeploy/
```
2、导入sample-data 相关：
```
Clone this project

git clone https://github.com/docdoku/docdoku-plm-sample-data.git
Run loadSample.sh or loadSample.bat depending on your OS

./loadSample.sh -u login -p password -h url [-w workspaceId]  
Parameters :

login : your account name (will be created) - required
password : your account password (will be created) - required
url : url of the DocDokuPLM instance server (http://localhost:8080) - required
workspaceId : then name of the workspace to be created - optional, will be generated if not specified
```

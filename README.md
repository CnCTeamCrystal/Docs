# Docs
개발 관련 문서 정리 
* REST API
* 사용 프레임워크(런타임 및 버전 상세)
* 사용 방법

## Example
### 사용 프레임워크(런타임 및 버전 상세 필요)
* Spring-Boot 1.5.6
* Maven 4.0.0

### 사용 방법
해당 jar 파일이 있는 곳에서 
java -jar 파일명.jar

### 데이터베이스
url=jdbc:mysql://localhost:3306/base_info
username=root
password=1234

# API
## Sign up
### URI
HTTP|URI
---|---
POST|/user/add/

### Parameter
Parameter|Parameter명|Data Type
---|---|---
id|User ID|Long
email|User E-mail|String
userName|User Name|String
password|User Password|String

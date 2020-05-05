# Vue CLI  
개념: 명령어를 통한 특정 액션을 수행하는 도구  

## 설정방법  
1. 노드버전 확인  
터미널을 열어서 노드 버전을 확인해야된다.(10이상이어야된다.)  
````
$ node -v
````  

2. NPM 버전 확인  
터미널을 열어서 NPM 버전을 확인해야된다.(6이상이어야된다.)  
````
$ npm -v
````  

3. Vue CLI 설치  
터미널에서 Vue CLI를 설치하는데, -g로하면 전체 디렉토리에 설정되는것 참고
````
npm install -g @vue/cli

//만약 위처럼 했는데 오류가 난다면 폴더에대한 권한이 없는 것이기 때문에 아래와 같이 한다.
sudo npm install -g @vue/cli
````  

## Vue CLI 프로젝트 생성, 실행 방법  
1. 생성
````
[Vue CLI 2.x]
vue init '프로젝트 템플릿 유형' '프로젝트 폴더 위치'
vue init webpack simple '프로젝트 폴더 위치'

[Vue CLI 3.x]
vue create '프로젝트 폴더 위치'
````  
만들때 default로 만들어줄것  
2. 실행  
````
해당 프로젝트 폴더로 들어간 다음에
npm run serve
````
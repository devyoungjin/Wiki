# TIL

*Today I learned.*

오늘 제가 배운 내용을 정리하는 공간입니다.

<Br>

## ToC

- [Programming Language](https://github.com/youngjinmo/TIL/tree/master/programming%20languages)
  - [Java](programming%20languages/Java.md)
    - [Java의 특징](/programming%20languages/Java.md#feature)
    - [Java의 철학](/programming%20languages/Java.md#philosophy)
    - [IDE없이 컴파일하고, 실행하기](/programming%20languages/Java.md#run-compile-without-ide)
    - [Wrapper Class](/programming%20languages/Java.md#wrapper-class)
    - [Date](/programming%20languages/Java.md#date)
    - [Javadoc](/programming%20languages/Java.md#javadoc)
    - [Math](/programming%20languages/Java.md#math)
    - [length, length(), size()](/programming%20languages/Java.md#length)
    - [==과 equals()](/programming%20languages/Java.md#equals)
    - [문자열 변환 함수](/programming%20languages/Java.md#touppercase)
    - [Lombok](programming%20languages/Java.md#lombok)
    - [JavaBean](programming%20languages/Java.md#javabean)
      - [JavaBean 규칙은 무엇이며, 왜?](programming%20languages/Java.md#rule-and-why)
      - [Bean 생성하는 법](programming%20languages/Java.md#create-javabean)
  - [Python](programming%20languages/Python.md)
    - [파이썬의 특징](programming%20languages/Python.md#feature)
      - [인터프리터 언어](programming%20languages/Python.md#feature-interpretor)
      - [인덴트](programming%20languages/Python.md#feature-indent)
  - [SQL](programming%20languages/Sql.md)
    - [AND 조건 조회](programming%20languages/SQL.md#order-and)
    - [LIMIT](programming%20languages/SQL.md#limit)
    - [DISTINCT](programming%20languages/SQL.md#distinct)
    - [연산처리](programming%20languages/SQL.md#sql-math)
- [Server-side](https://github.com/youngjinmo/TIL/tree/master/server-side)
  - [Spring Framework](https://github.com/youngjinmo/TIL/tree/master/server-side/spring)
    - [Spring Boot](/server-side/spring/spring-boot.md)
      - [Spring Boot 특징](/server-side/spring/springboot.md#feature)
      - [Spring Boot auto-configuration](/server-side/spring/springboot.md#config)
      - [에러페이지 핸들링 (a.k.a 404 커스터마이징 )](/server-side/spring/springboot.md#error)
    - [Spring Security](/server-side/spring/SpringSecurity.md)
      - [OAuth2](/server-side/spring/spring-security.md#oauth2)
    - [Template Engines](/server-side/spring/TemplateEngines.md)
      - [Mustache](/server-side/spring/TemplateEngines.md#mustache)
    - [JPA](/server-side/spring/JPA.md)
      - [Hibernate](/server-side/spring/JPA.md#hibernate)
  - [Django](/server-side/django.md)
- [Front-side](https://github.com/youngjinmo/TIL/tree/master/front-side)
  - [HTML](/front-side/html.md)
    - [details](/front-side/html.md#details)
  - [CSS](/front-side/CSS.md)
    - [word-break](/front-side/css.md#word-break)
    - [복수의 id에 CSS 적용](/front-side/css.md#apply-style-to-multiple-ids)
- [CS Knowledges](https://github.com/youngjinmo/TIL/tree/master/CS)
  - [HTTP](CS/network/HTTP.md)
    - [GET/POST](CS/network/HTTP.md#getpost)
    - [URI/URL](CS/network/HTTP.md#uri)
- [Devops](https://github.com/youngjinmo/TIL/tree/master/DevOps)
  - [Linux](DevOps/Linux.md)
    - [명령어](DevOps/Linux.md#linux-commands)
      - [Shell과 Kernel](DevOps/Linux.md#shell-kernel)
      - [find](DevOps/Linux.md#linux-find)
      - [Symbolic Link](DevOps/Linux.md#linux-symboliclink)
      - [grep](DevOps/Linux.md#linux-grep)
      - [터미널 결과 출력](DevOps/Linux.md#save-output)
      - [복수의 명령어 동시실행](DevOps/Linux.md#combine-commands)
      - [슬립모드 진입방지 \(caffeinate)](DevOps/Linux.md##caffeinate)
      - [시스템 재부팅](DevOps/Linux.md#ubuntu-reboot)
      - [서버시간 변경하기](DevOps/Linux.md#change-localtime)
      - [UTF-8 인코딩설정](DevOps/Linux.md#setup-utf8)
      - [호스트네임 변경하기](DevOps/Linux.md#hostname)
    - [Vi Editor](DevOps/Linux.md#linux-vi)
      - [입력 명령어](DevOps/Linux.md#vi-input)
      - [이동 명령어](DevOps/Linux.md#vi-move)
      - [파일 상태 명령어](DevOps/Linux.md#vi-filestatus)
    - 패키지 관리툴
      - [apt-get](DevOps/Linux.md#apt-get)
        - [update와 upgrade의 차이](DevOps/Linux.md#difference-between-update-upgrade)
        - [apt-get 패키지 설치/삭제하기](DevOps/Linux.md#install-remove)
        - [ubuntu에서 jdk, jre 설치하기](DevOps/Linux.md#install-jdk-jre)
        - [ubuntu에서 java 설치 경로 찾기](DevOps/Linux.md#which)
  - [Docker](DevOps/Docker.md)
    - [도커?](DevOps/Docker.md#intro)
    - [도커 설치](DevOps/Docker.md#installation)
    - [이미지 설치하기](DevOps/Docker.md#create-image)
    - [이미지 이름 변경하기](DevOps/Docker.md#rename-image)
    - [컨테이너 생성하기](DevOps/Docker.md#create-container)
    - [컨테이너 시작/중단하기](DevOps/Docker.md#control-container)
    - [도커 이미지 조회하기](DevOps/Docker.md#images)
    - [도커 컨테이너 조회하기](DevOps/Docker.md#ps)
    - [bash모드로 컨테이너 진입](DevOps/Docker.md#exec-imageid-bash)
    - [컨테이너 이름 변경](DevOps/Docker.md#change-container)
    - [컨테이너 삭제](DevOps/Docker.md#rm-container)
    - [이미지 삭제](DevOps/Docker.md#rmi-image)
  - [AWS](DevOps/AWS.md)
    - [Region과 Availability zone](DevOps/AWS.md#region)
    - [EC2 인스턴스의 기능](DevOps/AWS.md#ec2)
    - [터미널로 EC2 인스턴스 접속](DevOps/AWS.md#entering-ec2)
    - [EC2 locale 설정](DevOps/AWS.md#locale-ko-utf8)
    - [EC2 인스턴스(Ubuntu)에 JDK 설치하기](DevOps/AWS.md#install-jdk-ec2)
    - [awscli 설치하기](DevOps/AWS.md#awscli)
    - [Apache2 웹서버 실행하기](DevOps/AWS.md#start-apache2)
    - [키페어(.pem) 자동으로 읽어오기](DevOps/AWS.md#autoload-pem)
- [Others](https://github.com/youngjinmo/TIL/tree/master/Others)
  - [정규표현식](/Others/regex.md)
  - [언어별 정규표현식](/Others/regexByPL.md)
  - [Version Control / Git](/Others/Git.md)
    - [Staging과 Commit](/Others/Git.md#git-staging-commit)
    - [파일단위 아닌 변경사항 단위로 Staging하기](/Others/Git.md#git-add-p)
    - [Unstaging](/Others/Git.md#git-restore)
    - [git log 그래프로 보기](/Others/Git.md#git-log-decorate)
    - [브랜치 생성하기](/Others/Git.md#create-branch)
    - [브랜치 이동하기](/Others/Git.md#move-branch)
    - [브랜치 삭제하기](/Others/Git.md#delete-branch)
    - [원격 저장소 브랜치 삭제하기](/Others/Git.md#delete-origin-branch)
    - [브랜치 이름 변경하기](/Others/Git.md#change-branch-name)
    - [커밋 합치기 with rebase](/Others/Git.md#rebase-merged)
    - [커밋 순서 바꾸기 with rebase](/Others/Git.md#rebase-change-sequence)
    - [커밋메세지 변경하기 with rebase](/Others/Git.md#rebase-change-commit-m)
    - [Fork](/Others/Git.md#git-fork)
    - [PR](/Others/Git.md#git-pr)
    - [.gitignore](/Others/Git.md#git-gitignore)
    - [git config 설정](/Others/Git.md#git-config)
    - [Github Credential 저장](/Others/Git.md#git-credential)
    - [Github에 SSH 등록하기](/Others/Git.md#add-ssh)
    - [레파지토리 라이센스](/Others/Git.md#license)
  - [MacOS](/Others/MacOS.md)
    - [Homebrew](/Others/MacOS.md#homebrew)
    - [tree 패키지](/Others/MacOS.md#osx-package-tree)
    - [Xcode 대신 Command Line Tools 사용하기](/Others/MacOS.md#commandlinetools)
    - [xcrun error](/Others/MacOS.md#xcrun-error)
  - [Raspberry Pi](/Others/raspberryPi.md)
    - [SSH 활성화](Others/raspberryPi.md#enable-ssh)
    - [맥에서 라즈베리파이 SSH 접속](Others/raspberryPi.md#ssh-mac)
    - [도커 설치](Others/raspberryPi.md#install-docker)
  - [Errors](/Others/Errors.md)
    - [인텔리제이에서 class 파일이 decompile되었다고 할 때](/Others/Errors.md#decompile-class-intellij)
    - [Gradle이 정상적으로 작동하지 않을때](/Others/Errors.md#reimport-gradle)

<br>
---
title:  "AWS LightSail에 Django 프로젝트 배포하기 (+리눅스 명령어)"
date:   2021-03-17 03:17:22
categories: [jekyll]
tags: [AWS]
---


#### Linux 명령어

루트 권한을 줌 : <code>sudo </code>

파일이나 디렉토리의 소유주를 바꿈 : <code>sudo chown</code>

폴더 확인: <code>ls</code>

웹서버 유지하기 : <code>nohup python manage.py runserver 0.0.0.0:8000 &</code>



#### Tip

* 명령어가 안먹힐 땐 앞에 'sudo'를 붙여보기.. (권한문제일 가능성일 큼)

* WinSCP 설치 후,  drag&drop으로 업로드하면 편리하게 배포가능


#### Conference

Link: [AWS LighSail Django 배포 공식 튜토리얼] (https://aws.amazon.com/ko/getting-started/hands-on/deploy-python-application/)

Link: [아마존 LightSail 파일 업로드 문제] (https://darkstart.tistory.com/17)

Link: [AWS web server 유지시키기] (https://paphopu.tistory.com/entry/AWS%EC%97%90%EC%84%9C-SSH-protocol%EC%9D%B4-%EC%A2%85%EB%A3%8C%EB%90%98%EB%8F%84-web-service%EB%A5%BC-%EC%9C%A0%EC%A7%80%EC%8B%9C%ED%82%A4%EB%8A%94-%EB%B2%95-nohup)

Link: [WinSCP로 AWS에 파일 업로드하기] (https://pjs21s.github.io/Winscp/)

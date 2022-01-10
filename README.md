
## 실행방법

```
mkdir GITLAB_HOME
chmod 777 GITLAB_HOME
sh startup.sh up (docker-compose up -d)
(한10분후, http://127.0.0.1:8080 접속)

* root 패스워드
docker exec -it gitlab cat /etc/gitlab/initial_root_password 

```

## root로그인후
```
1.우상단 설정 (preferences)
 - 테마는 Dark Mode, 문법 Dark 테마
 - 언어는 Korea

2.좌상단 menu > Admin
 - 좌메뉴 설정 > 가입제한 > 신규가입시관리자승인(체크없앰,Require admin approval for new sign-ups) 

```

## 가입
```
First,Last Name:  sbs/pds
Username: sbspds
Email: sbspds@sbspds.com
Password: sbspdssbspds

(필요시, root 로그인후, 승인)
1. 한글로 변경
2. Create new Project > Crete from template > GitLab Cluster Management
 - Project name: sbspds
 - Visibility Level: Public





```

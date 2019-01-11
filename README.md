# Basic Workflow
```sh
$ git init
$ git status #빨간색확인
$ git add .
$ git status #초록색 확인(초록색만 커밋됨)
$ git commit -m '짧고 간결하고 현재형'

#github, bitbucket, gitlab etc... remote repo 를 생성
$ git remote add origin <REMOTE REPO URL.git>
$ git push (-u origin master) #첫번째만

#다른 컴퓨터라면,
$ git clone <REMOTE REPO URL.git> #downloadZIP => .git 없음ㅠㅠ
#작업작업
$ git add . && git commit -m 'MSG' && git push 
$ git add . ; git commit -m 'MSG' ; git push
# 한번에 작업 가능/ repo가 아닌곳에서 진행하면 &&는 에러남.진행안됨 ;은 에러나도 무시하고 진행

$ git pull
```
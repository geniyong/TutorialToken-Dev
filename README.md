#Tutorial-Token
##### ref. https://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin
##미리설치조건
1.truffle 설치
2.ganache 설치

## 템플릿 준비과정
```
mkdir oz-workspace
cd oz-workspace
truffle unbox tutorialtoken
npm install openzeppelin-solidity@1.12.0
```

BUT! 그냥 클로닝하면 위의 과정 모두 생략

## 실행방법
1. Ganache 실행
2. 프로젝트 폴더 내에서 명령실행
```
truffle console --network development
>truffle(development) migrate --compile-all --reset
>Ctrl+C *2
npm run dev
```
3. 127.0.0.1:3000 웹 접속
4. metamask ganache 연동 후 테스트 진행
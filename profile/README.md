### 👋🏻 사용 방법
- 팀별 Repository를 생성하여 pintos clone
  - pintos12-team0{팀 번호} 로 리포지토리 생성

```
git clone --bare https://github.com/casys-kaist/pintos-kaist.git
cd pintos-kaist.git
git push --mirror https://github.com/SWJungle4A/{팀 리포지토리}.git
cd ..
rm -rf pintos-kaist.git
git clone https://github.com/$SWJungle4A/{팀 리포지토리}.git
```

### ☝️ 커뮤니티 규칙
- 다른 팀 Repo. 임의 수정 금지

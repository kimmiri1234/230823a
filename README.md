## 230823 ##
### 사용 방법 ###
1. 로컬 저장소 생성<br>
`$ git init`

2. README.md 파일 생성<br>
`$ git add .`<br>
`$ git commit -m "README.md 파일 생성"`

3. 온라인 저장소 생성<br>
`$ git remote add origin https://repo주소.git`<br>

4. README.md 파일 온라인 저장소에 업로드<br>
`$ git push -u origin main`

### github에서 내려 받기 ###
`$ git pull origin main`

### clone과 pull 특징 ###
1. clone : 로컬에 저장소가 없는 경우. 저장소 자체를 복사
2. pull : 로컬에 연결된 저장소 있는 경우. 저장소 안에 있는 파일 내려받기

### 충돌(CONFLICT)시 해결 방법 ###
__ 충돌 이유 __
하나의 문서가 온라인과 로컬 각 각 수정이 일어났기 때문
__ 해결 __
1. pull을 이용하여 온라인 저장소에 로컬로 파일 내려받기
2. 받은 로컬 저장소의 문서를 수정 후 commit, push
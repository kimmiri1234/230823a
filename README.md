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
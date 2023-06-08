# 플러그인 사용 방법

streamlink-plugin-kick과 마찬가지로 다운로드 한 경로를 --plugin-dirs 뒤에 넣어주시면 됩니다.

## 사용 예시
```bash
streamlink --plugin-dirs .\streamlink-plugin-kick-advanced-master https://kick.com/blahblah ...
```

## 리눅스 사용자 필수 사항
리눅스는 chmod를 통해 파일 권한을 수정해주셔야 합니다 
```bash
chmod +x ./streamlink-plugin-kick-advanced-master/linux/*
```
# 플러그인 사용 방법

streamlink-plugin-kick과 마찬가지로 다운로드 한 경로를 --plugin-dirs 뒤에 넣어주시면 됩니다.

## 사용 예시
```bash
streamlink --plugin-dirs .\streamlink-plugin-kick-advanced-master https://kick.com/blahblah best -o output.mp4
```

## 리눅스 사용자 필수 사항
리눅스는 chmod를 통해 파일 권한을 수정해주셔야 합니다 
```bash
chmod +x ./streamlink-plugin-kick-advanced-master/linux/*
```

## 오라클 클라우드 사용자 확인 사항
오라클은 aarch64 아키텍쳐 기반이므로 executable 파일을 교체해줍니다
```bash
cd ./streamlink-plugin-kick-advanced-master
rm -rf ./linux
mv ./oracle ./linux
chmod +x ./linux/*
```

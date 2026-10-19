# app-releases

테스트용 안드로이드 APK 배포 저장소입니다. 앱 소스는 각 앱의 비공개 저장소에 있고, 여기에는 빌드된 APK와 버전 정보만 올라갑니다.
(배포 도구: 개발 PC의 `C:\project\android\APP`)

## 처음 설치 (폰에서 링크를 눌러 받기)

| 앱 | 최신 APK |
|---|---|
| 하루컷 | https://github.com/ssoon0420/app-releases/releases/download/harucut-latest/harucut.apk |
| 사부작 | https://github.com/ssoon0420/app-releases/releases/download/sabuk-latest/sabuk.apk |
| 다시봄 | https://github.com/ssoon0420/app-releases/releases/download/dasibom-latest/dasibom.apk |
| iBridge | https://github.com/ssoon0420/app-releases/releases/download/ibridge-latest/ibridge.apk |

한 번 설치한 뒤에는 앱을 열 때 새 버전이 있으면 "업데이트" 안내가 뜹니다.

## 구조

- `<앱>-v<번호>` 릴리스: 그 버전의 APK와 변경 내용(앱별 최근 5개만 남김)
- `<앱>-latest` 릴리스: 앱이 읽는 `version.json` + 최신 APK(`<앱>.apk`)

# Scan :)
---

### Introduction
---
문서를 스캔하여 정방향으로 바꾸고 텍스트를 추출하는 코드입니다.

---
### Description
---
+ OpenCV 오픈소스 라이브러리를 사용합니다.
+ pytesseract를 사용합니다.
+ 추출한 텍스트를 해당 폴더에 text.txt 이름으로 저장합니다.

---
### How to use
---
터미널 환경에서 python 코드를 실행합니다.

python3 + fileName + imageName

ex)
```
python3 scan.py paper.png
```

아무 키를 눌러 화면을 넘기면 text.txt 파일로 텍스트가 저장됩니다.

---
### Caution
---
+ mac 환경에서 개발되었습니다.
+ OpenCV, pytesseract, numpy를 설치 후 실행해야합니다.
+ 이미지내 문서의 꼭지점이 모두 나와야합니다.

---
### Reference
---
+ [OpenCV](https://opencv.org)
+ [OpenCV 예제 블로그](https://cori.tistory.com/132)

---
### License
---
Apache 2.0 라이선스
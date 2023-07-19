# Deep Learning 용어사전
딥러닝 문서 번역 시 용어 통일성을 위해 용어사전을 만들었습니다.   
   

## 변경사항 검토하기
문서 수정을 위해 레포지토리를 `fork`하여 문서를 수정합니다. 설치 및 빌드 순서는 아래와 같습니다.
   
- 주피터 북 동작을 위한 라이브러리를 설치합니다.
```
pip install -r requirement.txt
```

- 변경점을 주피터 북에 적용하기 위해 빌드를 수행합니다.
```
jupyter-book build website
```

- 자신의 컴퓨터의 브라우저로 `index.html`파일을 실행합니다.
```
cd ./website/_build/html/index.html
```
수정된 사항이 잘 반영되었는 지 확인합니다.

- 변경된 문서를 웹에 배포합니다.
```
ghp-import -n -p -f ./website/_build/html
```
   
## 변경사항 반영하기
- PR Template을 이용하여 반영을 요청합니다.
Please use this [PR Template](https://gist.github.com/gabrielwithappy/55affa9f9c3fc588b5830ce9a0cd1bd1)
Thank you for your support in advance


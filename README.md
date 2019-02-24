# 개요

이 것은 Siraj Raval의 유튜브 [영상](https://youtu.be/7vunJlqLZok)을 위한 코드입니다. 

StockIT은 머신러닝 웹 게임으로, 사용자들이 AI와 주식매매로 경쟁할 수 있습니다. 무작위로 종목과 과거의 날짜가 선택됩니다. 주가는 그 날짜로부터 365일간 지속됩니다. 주가가 움직이는 동안, 사용자는 AI와 주식매매로 경쟁하게됩니다.

Pandas와 Scikit Learn은 주가 예측을 위한 선형회귀 모델을 개발하는데 쓰입니다. D3와 React는 데이터를 차트로 그려주고, 리더보드의 랭킹을 업데이트하는데에 사용됩니다. 데스크탑과 모바일에 최적화되어 있습니다.

http://www.StockIT.tech


## 시작하기

로컬 호스트에서 개발서버를 돌리기 위해서는, 먼저 프론트엔드를 위한 필수 npm 패키지를 모두 설치해야합니다.

`cd client`

`npm install`

이제, 설치가 끝났으면, 프론트엔드 서버를 3000포트로 띄울 수 있습니다.

`npm start`

다음으로는, 필수적인 파이썬 패키지를 설치할 차례입니다.:

`cd ..`
`pip install -r requirements.txt`

아재 추가로 터미널을 열어, 백엔드 서버를 5000포트로 실행합니다.

`python -m flask run FLASK_APP=app.py`

`flask run`

이제 셋업이 끝났군요!

## 빌드할 때 다음 것들이 필요합니다

* React
* D3
* Python
* Flask
* Pandas
* Scikit Learn

## 저자

Austin Tackaberry

## License

이 프로젝트는 MIT License를 따릅니다. - LICENSE.md 파일에서 세부 정보를 확인하세요

## 권리

이 코드의 권리는 [austintackaberry](https://github.com/austintackaberry/stocks)에게 있습니다. 저는 단지 사람들이 쉽게 시작할 수 있도록 편집했을 뿐입니다.

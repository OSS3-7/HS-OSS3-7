# ZXING
---

### 1.Zxing 이란? (Zebra Crossing)
안드로이드에서 QR코드 생성 및 QR스캔, Barcode 스캔에 도움을 주는 구글에서 제공하는 오픈소스


### 2.특징
-내장 카메라 앱을 이용하여 바코드나 Qr코드를 스캔하고 인코딩된 데이터를 검색할 수 있게한다. 
-1차원 또는 2차원의 그래픽 QR코드, 바코드를 인식하는데 코드에 지정된 웹 주소, 지리학적 좌표, 텍스트등에 바로 넘어갈 수 있게 할 수있다.
-QR코드를 찍으면 YUV라는 포멧으로 데이터를 보내주는 데 데이터를 변환하여 사용해야하는 데  ZXing자체에 데이터 변환소스가 포함되어있다.
(PlanarYUVLuminanceSource)


### 3.기능
내장 카메라 앱을 사용하여 바코드나 Qr코드를 스캔하고 인코딩된 데이터를 검색할 수 있게한다. 
1차원 또는 2차원의 그래픽 QR코드, 바코드를 인식하는데 코드에 지정된 웹 주소, 지리학적 좌표, 텍스트등에 바로 넘어갈 수 있게 할 수있다.
이미지 매트릭스나 QR코드 정보를 저장하는 matrix는 Hashtable 와 Vector로 저장


### 4.제약사항
<img src="Open Source Research(오픈소스 자료조사)/스크린샷 2022-12-04 오전 2.12.35.png">
format에 맞는 제품을 사용해야한다.



### 5.알고리즘

- 카메라를 연 후 프리뷰를 가동한다.
- 카메라로부터 지속적으로 영상을 받아들인다. [2]
- 영상에서 밝기값만 추출[3]하여 이를 기반으로 이진화를 수행한다.[4]
- Detector 클래스를 통해 QR코드 영역을 찾아냈다.
- 찾아낸 영역을 Decoder 클래스를 통해 해석한다.
- 결과 값과 결과 영상을 리턴
- 결과 값을 분석하여 URL일 경우 탭하면 인터넷으로 연결되도록 한다.
- 화면에 결과 영상과 결과 값을 출력한다.



### 6.우리서비스에서의 이용 

3번의 방법으로 이용하여 교수님이 출석 QR코드를 발행하고 모니터에 띄우면 학생들은 QR코드를 찍고 출석인증한다.


### 7.라이선스

APACHE 라이선스 2.0 라이선스
—————————————————————————————————
Copyright (C) 2012-2022 ZXing authors, Journey Mobile

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

———————————————————————————————————

### 8.Zxing 링크 (+코드)

https://github.com/zxing/zxing

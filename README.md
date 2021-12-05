# HuPoE

| **제목**   |중/소 산업현장 안전시스템 프로젝트 |
| :---: | :---: | 
| **부제**   |Human Pose Estimation Project with PyQt, Pyside|
| **개발자**   |`변의혁`, `구태완`|
| **개발기간**   |`2021.09` ~ `2021.11 `| 
| **포트폴리오 링크** | [포트폴리오 보기](https://www.miricanvas.com/v/1ojqh0) |
| **사용기술** | `Python`,`Tensorflow`,`Keras`,`Mediapipe`,`Dlib`,`PyQt5`,`Pyside2` |
| **버전** | v0.0 |

## 목차
1. [개요](#개요)
2. [내용](#내용)
3. [결과](#결과)



## 개요
### 기획의도
 - 제품을 생산하는 공장 혹은 건설현장에서는 크고 작은 안전사고가 발생하고 있다. 특히 안전관리 사각지대로 꼽히고 있는 중ㆍ소형 건설현장 및 중소기업 산업현장 같은 경우 작업인원이 많지 않기 때문에 혼자 작업을 하는 일이 발생하고 그 경우 사고 발생 시 사후 조치가 힘들어 인명피해로 이어지기도 한다. 이를 방지하고 효율적인 대처를 위해 기획하였다. 영상 기반 행동 패턴 분석을 활용한 안전 시스템은 인공지능과 사물인터넷 등 4차 산업기술 사용으로 대규모의 비용이나 인력 투입 없이 사고 및 위험요소를 사전에 감지하거나 사고가 발생한 인원 발생 시 신속한 초동대처로 위험요소를 선제적으로 예방하는 데 목적이 있습니다.

### 개발일정
![20211205_014826](https://user-images.githubusercontent.com/84761763/144717566-e9187c72-b6f1-480a-933a-8295591ee489.png)

### 데이터 셋
 - pass
 - [학습된 데이터 셋](https://drive.google.com/file/d/1GcxSzzDbk1N9Z6yUkTPrt-YcfjGv6lJJ/view?usp=sharing) 다운 받아 파일 내에 압축 풀어서 사용
 - models 폴더는 해당폴더에 놓고 사용, font 내 폴더는 windows/font에 복사하거나 실행하여서 사용
 - 학습결과\n

![20211205_182157](https://user-images.githubusercontent.com/84761763/144740898-6352bf75-363d-4c0f-bdb0-422806e166e4.png)


## 내용
### 주요 기능
 - meidapipe 이용 사람의 관절 추정
 - Dlib이용 사람얼굴 구분하여 신원특정
 - PyQt5, Pyside2 이용 로컬에서 이용가능한 프로그램 제작
### 파일 구성
#### test.py
- pass
#### test2.py
- pass

## 결과
 - [시뮬레이션 동영상 링크](https://youtu.be/lE7QpYeMWs0) 

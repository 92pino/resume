정진배 - (Pino)
================

### Pino's Creative Factory😀
![GitHub last commit](https://img.shields.io/github/last-commit/kawoou/resume.svg)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://open.kakao.com/o/sBGccogb)

* Email: [jjb8382@gmail.com](mailto://jjb8382@gmail.com)
* Blog: [92pino.github.io](http://92pino.github.io)
* Github: [github.com/92pino](https://github.com/92pino)
* KakaoTalk: [open.kakao.com/o/sBGccogb](https://open.kakao.com/o/sBGccogb)
* Trello: [Trello Resume](https://trello.com/b/A4uJsWdw/resume)

<br/>

## 목차

* [프로젝트](#프로젝트)

## 프로젝트

**SungsuHack (성수핵)**

>  성수 근처 감성 카페 리스트

[![Video Label](https://user-images.githubusercontent.com/45158632/65492347-b3660800-deeb-11e9-80a3-b5bf76244cf0.PNG)](https://www.youtube.com/watch?v=Rzkk7k9iwK0&feature=share?t=6s)
![main](https://user-images.githubusercontent.com/45158632/65492539-135cae80-deec-11e9-8a91-6af9ddaeb92d.PNG)

20190520 - 해커톤 기획 시작 ~ 20190524 - 프로젝트 완료 및 발표

[ 해커톤 리뷰 내용 ]
1. 팀 구성 소개 + 초기 기획안 + 기획 의도
    1) 정진배, 홍원표
    2) 예쁜카페들이 많은 성수동. 그 중에서도 인스타그램 등의 성지 카페들을 소개하는 사진형 어플
    3) 성수동을 방문하는 사람들이 실제로 사용할 수 사용성 높은 앱을 기획하는 것을 목적으로 함


2. 팀 역할 분배
    1) 정진배 - 첫번째 메인페이지(커스텀 컬렉션뷰 구현), 맵뷰 상의 어노테이션, 저장페이지 구현, 디테일뷰상의 인스타그램 연결, 카카오 지도 연결
    2) 홍원표 - 기획, 컨텐츠, 데이터 모델링, 맵뷰상의 컬렉션뷰 구현, 디테일뷰 구현


3. 최종 결과물 소개
[성수 핫플레이스](https://www.youtube.com/watch?v=Rzkk7k9iwK0&feature=share)

    1) 성수동의 핫플레이스 카페들을 핀터레스트 방식(사진형)으로 보여주고, 지도에서도 그 카페들을 확인할 수 있도록 함.
    2) 좋아요(저장)를 누른 컨텐츠들을 나중에도 확인할 수 있도록 함
    3) 디테일페이지에서는 각 카페들의 디테일 사진을 10장 확인할 수 있고, 주소 등의 정보를 확인가능함
    4) 디테일페이징서는 1.인스타그램의 태그 연동을 통해, 여러 사람들이 해당 카페에서 찍은 사진들을 확인할 수 있도록 하고,   카카오지도에 연동하여서 해당 카페를 찾아가기 쉽도록 함


4. 기획 대비 완성률  /  개발 과정에서 초기 기획과 달라진 점
    1) 완성률: 70% / 100%
    2) 개발 과정에서 초기 기획과 달라진 점:
        - 좋아요(저장) 컨텐츠들을 싱글톤으로만 구현하고  유저디폴트에 저장하지 못해서 정보가 저장이 안됨
        - 검색기능이 구현이 안됨
        - 맵뷰 상에서 컬렉션뷰의 컨텐츠 클릭시 어노테이션으로 이동은 되나, 콜아웃 선택된 상태를 구현하지 못함.

**Travelog**

> 여행 기록 어플

개요 : 여행 기록을 감성적인 사진과 함께 기록해 추억을 돌아보게 하는 사진 기록 어플
참여 인원 : iOS 2명
구현 부분
- SK open API의 JSON data 를 parsing 하여 날씨 정보를 사용함
- CoreData 를 활용하여 데이터 베이스 구현
- MapView를 활용하여 위치정보를 저장 할 수 있

- 사용기술 - Swift, CoreData, YPImagePicker

**Yanolja Copy App**

> 야놀자 클론 앱

개요 : 기존 야놀자 앱 서비스를 기반으로 같은 형태의 서비스를 만들어보는 클론 프로젝트
개발 기간 : 2019.07.01 - 08.09
참여 인원 : iOS 3명, 백 엔드 3명, 프론트 엔드 4명
구현 기능 : 내 주변 숙소 리스트, 숙소 검색 기능, 숙소 예약 서비스
Github Link : https://github.com/final-project-yanolja/iOS_Team

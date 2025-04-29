# mybudongsan
부동산 실거래가 조회 플러터 앱 만들기

0. 기획단계
    ① 부동산 앱의 목적과 기능 정의하기
    ② 부동산 앱의 화면 구성과 흐름도 작성하기
    ③ 부동산 앱의 디자인 가이드라인 선정하기
    ④ 부동산 앱에 필요한 데이터 모델과 API tjfrPgkrl

1. My 부동산앱 SWOT 분석
   | **S(강점)** | **W(약점)** |
   |:---:|:---:|
   | - 앱을 개발하며 전반적인 플러터 기능을 배울 수 있음.<br>- 부동산 앱을 만들어 볼 수 있다. | - 상용화하려면 추가 기능이 필요함.<br> |
   | **O(기회)** | **P(위협)** |
   | - 플러터로 보기 좋은 디자인의 부동산 앱을 만든다.<br> | - 기능이 단순해 다순한 서비스가 되기 쉬움.<br> |

2. 화면 흐름도
    2.1 부동산 거래가 조회 앱 흐름도
        ![앱 흐름도]<img src="/md_img/app_flow.png" height=80% />

    2.2 화면 흐름도
        |     화면 페이지    |        설명       |
        |:---------------:|:----------------:|
        | ![1)인트로]<img src="/화면흐름도/md_img/1.인트로페이지.png" height=80% /> | - 이 페이지는 인터넷 연결 상태를 확인한다.<br>-온라인 상태라면 앱의 이름과 아이콘을 보여준 후, 2초 후에 메인 페이지로 자동 전환된다. |
        | ![2)메인]<img src="/화면흐름도/md_img/2.메인페이지-지도페이지.png" height=80% /> | - 구글 지도 플랙폼을 이용하여 자도를 표시함. |
        | ![3)상세1]<img src="/화면흐름도/md_img/3.상세1-필터페이지.png" height=80% /> | - 돋보기 아이콘을 클릭하면 검색필터를 표시해 검색 조건을 설정함. |
        | ![4)상세2]<img src="/화면흐름도/md_img/4.상세2-검색결과페이지.png" height=80% /> | - 사용자 정의 아이콘을 이용해 지도에 검색결과를 표시함.<br>-아이콘을 터치하면 자세한 내용을 확인할 수 있다. |
        | ![5)즐겨찾기]<img src="/화면흐름도/md_img/5.즐겨찾기페이지.png" height=80% /> | - 자신의 즐겨찾기 아파트를 등록한다.<br>-해당 페이지에서는 로그인 상태라고 가정함. |
   





## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

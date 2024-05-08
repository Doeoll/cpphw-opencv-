opencv 사용법

1.opencv 다운로드
2.c 바로 밑에 압축풀기
3.visual studio 열기
4.프로젝트 > 속성 > c/c++ > 일반 > 추가 포함 디렉토리 > 편집 > C:\opencv\build\include 추가
5.프로젝트 > 속성 > 링커 > 일반 > 추가 라이브러리 디렉토리 > 편집 > C:\opencv\build\x64\vc16\lib 추가
6.프로젝트 > 속성 > 링커 > 입력 > 추가 종속성 > 편집 > opencv_world490d.lib(C:\opencv\build\x64\vc16\lib에 위치함) 추가
7.시스템 환경 변수 편집 > 환경 변수 > PATH > 편집 > 찾아보기 > C:\opencv\build\x64\vc16\bin 추가
8.opencv_world490d.dll 파일 프로젝트 디렉토리에 추가
9.코드 작성 및 디버그

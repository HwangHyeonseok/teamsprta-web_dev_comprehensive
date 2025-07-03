# 팀스파르타 [왕초보] 웹개발 종합반 커리큘럼 개선안 도출
<div style="display: flex; align-items: center;">
  <div style="margin-right: 20px;">
    <strong>강의 링크 :</strong><br/>
    <a href="https://online.spartacodingclub.kr/enrolleds/67852e956df5cd9a6148b147/rounds/677b4bb1711896fc7b5a6d0e/roadmap" target="_blank">
      스파르타코딩클럽 강의 보기
    </a>
  </div>
  <div>
    <img src="https://github.com/user-attachments/assets/3aeb8c7e-ec22-4f5c-a6d7-f68499cf3b21" alt="lecture" width="200"/>
  </div>
</div>

## 목차
[1. 강의 수강 후 커리큘럼 도출](#커리큘럼-도출)<br>
[2. 리뷰 데이터 수집 및 현상 분석](#리뷰-데이터-시각화-및-분석_현상-파악)<br>
[3. 개선안 및 아이디어 제시](#개선안-아이디어-제시)<br>
<br><br>

## 커리큘럼 도출
- HTML+CSS -> Javascript+JQuery -> Firebase -> 배포(Github Actions) <br><br><br>
![curriculums](https://github.com/user-attachments/assets/1b1bb796-2df9-4ddc-a0d5-fd2681e35a6e)

### 추억앨범 프로젝트 (album/index.html)
#### 완성 사이트 : https://hwanghyeonseok.github.io/teamsprta-web_dev_comprehensive/album/index.html
[HTML+CSS]
- 1-11 [추억앨범] 프로젝트 1
- 1-12 [추억앨범] 프로젝트 2

[JQuery]
- 3-2 [추억앨범] 제이쿼리 적용 1
- 3-3 [추억앨범] 제이쿼리 적용 2

[Firebase]
- 4-4 Firestore Database 시작하기 (firebase 세팅)
- 4-5 [addDoc] Firestore Database에 데이터 넣기
- 4-6 [addDoc] 데이터 넣고, 화면 새로고침 하기(location, alert)
- 4-7 [getDocs] Firestore Database에서 데이터 가져오기
- 4-8 앨범 데이터 카드 불러오기 기능 돌아보기

[배포]
- 5-6 Github Pages로 배포하기
- 5-7 배포한 것 수정하기 및 주의 사항
참고 : fetch 데이터를 받을 때 강의에서는 HTTP를 사용하지만, GitHub Pages 정책 상 HTTPS만 받아올 수 있으므로 배포판은 fetch 적용이 되지 않았음.

### 스파르타 플릭스 (spartaflix/index.html)
#### 완성 사이트 : https://hwanghyeonseok.github.io/teamsprta-web_dev_comprehensive/spartaflix/index.html
[HTML+CSS]
- 2-2 [스파르타플릭스] 프로젝트 1
- 2-3 [스파르타플릭스] 프로젝트 2
- 2-4 [스파르타플릭스] 프로젝트 3

[JQuery]
- 3-4 [스파르타플릭스] 제이쿼리 적용 1
- 3-5 [스파르타플릭스] 제이쿼리 적용 2

[Firebase]
- 4-4 Firestore Database 시작하기
- 5-2 [addDoc] 영화 데이터 넣기
- 5-3 [getDocs] Firestore Database에서 데이터 가져오기

[배포]
- 5-6 Github Pages로 배포하기
- 5-7 배포한 것 수정하기 및 주의 사항
참고 : fetch 데이터를 받을 때 강의에서는 HTTP를 사용하지만, GitHub Pages 정책 상 HTTPS만 받아올 수 있으므로 배포판은 fetch 적용이 되지 않았음.

### 3주차 숙제 (3week_homework/index.html)
#### 완성 사이트 : https://hwanghyeonseok.github.io/teamsprta-web_dev_comprehensive/3week_homework/index.html
- 3주차 숙제 HTML, CSS를 활용하여 화면 만들기 + (자체적으로 jQuery를 사용하여 음식 추가 기능 구현)


### 5주차 숙제 (5week_homework/index.html)
#### 완성 사이트 : https://hwanghyeonseok.github.io/teamsprta-web_dev_comprehensive/5week_homework/index.html
- 5주차 숙제 javascript + firebase 를 활용하여 데이터 추가 + 데이터베이스에 저장 + 데이터 화면에 뿌려주기
<hr>

## 리뷰 데이터 수집
- HRD-NET 1회차~30회차 웹 스크래핑 진행 (324개의 리뷰 데이터 수집) <br><br>
![image](https://github.com/user-attachments/assets/40cf8142-5166-4414-9618-2a965b2caeef)

## 리뷰 데이터 시각화 및 분석_현상 파악
- 긍정 키워드 중에서 쉽다/이해하기 쉽다는 의견이 다수 나왔으나, 부정 키워드에서도 어렵다는 의견이 다수 나왔음
- 상관관계 분석 : 쉽다/이해하기 쉽다는 의견을 낸 사람 중 대다수는 개발 경험이 있는 경우이고 어렵다는 의견을 낸 대부분은 개발 경험이 부족하거나 처음인 경우이다.
![analyze](https://github.com/user-attachments/assets/b73614d6-65dd-4fae-96b3-2e9b5aa420e9)

## 개선안 아이디어 제시
- 해당 강의의 체류 기간 로그 데이터를 통해 난이도를 파악 (체류 기간이 길다면 실습 중 어려운 점이 있을 가능성이 높음) -> 실무자는 원인을 파악하고 난이도 재조정이 가능함
- 실제 코딩테스트 사이트인 '코드트리' 사이트에서는 체류 시간으로 난이도를 평가하고 있음
 ![Solution](https://github.com/user-attachments/assets/9366efc0-ae59-4d58-bb96-18f35ba4ecc4)

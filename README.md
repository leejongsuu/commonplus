# 커먼플러스🛒 : 쇼핑몰 통합 관리 서비스
<div align="center">
  <img width="500" alt="main_image_5" src="https://github.com/harin1212/spring/assets/99604087/167173cf-b706-446e-a5ca-eaf6d64f5eae">
    <img width="500" alt="main_image_3" src="https://github.com/harin1212/spring/assets/99604087/5175999e-154f-44ac-99e3-7f62c11e43e1">
</div>

- 배포 URL : https://commonplus.store/
- Test ID : test@test.com
- Test PW : qqqqqqqq!

<br>

## 프로젝트 소개

- 커먼플러스는 ‘다중 플랫폼 쇼핑몰’ 통합 관리 서비스 입니다.
- 쿠팡, 11번가, g마켓, 옥션 셀러들은 자신의 쇼핑몰 계정을 등록하고, 보관상품 등록 + 쇼핑몰 그룹 등록을 통해 외부로 상품을 등록할 수 있습니다.

<br>

## 시작가이드

### 환경
* java 17
* Gradle 8.x
* Spring Boot 3.2.x
* MySQL 8.x

<br>

### 실행과정
<pre><code>git clone https://github.com/commonplus/commonplus-back.git
cd commonplus-back
build gradle
gradlew run
</code></pre>
<br>

### 환경변수
<br>

### 폴더 구조 설명
* address : 외부 쇼핑몰 주소록 관리
* category : 외부 쇼핑몰 카테고리
* cs : 외부 쇼핑몰 고객 문의 관리
* mall : 외부 쇼핑몰 계정 관리
* mallGroup : 외부 상품 등록시 필요한 데이터 관리
* notification : 외부 쇼핑몰 고시정보 관리(11번가)
* order : 외부 쇼핑몰 주문 관리
* product : 등록상품 관리
* shipping : 외부 쇼핑몰 출고지 관리
* shopProduct : 외부 쇼핑몰 상품 등록 관리
* user : 사용자 계정 관리

<br>

### 데이터베이스 설정
<pre><code>create database commonplus character set utf8mb4 collate utf8mb4_general_ci;</code></pre>

<br>

### ERD
<img src="https://github.com/commonplus/commonplus-back/assets/78680486/c0cec1da-f868-4f07-b12a-fd327801eb65">

***

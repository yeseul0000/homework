### Mission-03

## 1. 과제 구현 사항

주어진 netflix figma 시안을 구현

## 2. 구현 계획

1. 초기 계획 세우기

- 마크업 <br/>
- 브레이크 포인트 설정<br/>
- 반응형 웹 구현 계획<br/>

2. CSS로 배치 진행
3. CSS로 반응형 및 디자인 진행

## 3. 구현

### 3-1. 초기 계획 세우기

#### 1. 마크업
![image](https://github.com/yeseul0000/homework/assets/148925429/5401e001-2c06-487b-96f5-745ba6f0c5cd)
(첨부한 이미지는 팀원이 만든 자료)

3조 회고조 팀원과 같이

1. 시안을 보고 각자 마크업 해보기
2. netflix 사이트에 들어가 본인이 마크업 한 것과 비교하여 마크업 수정
   하는 작업을 진행하였다.

#### 2. 브레이크 포인트 설정

일반적인 브레이크 포인트(주1)를 참고하여 모바일 480px, 타블렛 1280px을 브레이크 포인트로 잡았다.

(주1 브레이크 포인트)<br/>
~ 480px: 모바일 세로<br/>
481px ~ 768px: 모바일 가로, 타블렛 세로<br/>
769px ~ 1024px 또는 1280px: 타블렛 가로, 노트북<br/>
1025px 및 1281px ~: 데스크탑<br/>

#### 3. 반응형 웹 구현 계획

<b>1. header</b>

   max-width: 1280px(타블렛)

   - 좌우 padding 값 감소

   max-width: 480px(모바일)

   - 언어 선택과 로그인 버튼 사이 간격 감소
   - logo 사이즈 감소

<b>2. main</b>
   
   max-width: 1280px

   - 글자 및 줄간격 조정

   max-width: 480px(모바일)

   - 좌우 padding 값 조정
   - input과 button 스타일 변경 및 줄바꿈 됨
   - 전체 width 조정

<b>3. footer</b>
   
   max-width: 1280px

   - ul li 를 3줄로 변경

   max-width: 480px(모바일)

   - ul li 를 2줄로 변경
   - 좌우 padding 값 조정

### 3-2. 구현

마크업 => 큰 배치 잡기 => 디테일 잡기 => 브레이크 포인트 구현 <br/>
* 진행하며 반응형으로 적절하게 작동하는지 중간중간 체크<br/>

### 3.3 마무리 체크리스트
[o] html 문법검사를 진행하였는가? <br/>
[x] css 문법 검사를 진행하였는가? <br/>
[o] 클래스 이름이 알기 쉽게 되어있는가? <br/>
[o] 코드를 읽는 데에 어려운 부분은 없는가. <br/>
(주석을 넣고 해결 할 수있으면 그렇게 해결)

## 4. 후기
큰 배치를 잡는 데에 어려운 부분은 없었다. <br/>
하지만 디테일한 디자인을 잡는 과정에서 잘 안 되거나 귀찮거나 하는 이유로 적당히 그럴듯 하게 보이는 데까지만 만들었다.<br/>
실무에서는 용납 안 해주겠지? 귀찮을 거 같다. 자그마한 요소 때문에 한 두시간 날리게 된다면 기분이 어떨까?

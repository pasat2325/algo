# [Gold II] 너 봄에는 캡사이신이 맛있단다 - 15824 

[문제 링크](https://www.acmicpc.net/problem/15824) 

### 성능 요약

메모리: 5536 KB, 시간: 60 ms

### 분류

수학, 정렬, 조합론, 분할 정복을 이용한 거듭제곱

### 제출 일자

2025년 7월 8일 11:44:26

### 문제 설명

<p>주헌이는 매운맛을 좋아한다. 정확히는, 매운맛을 먹음으로써 느낄 수 있는 고통에서 희열을 느끼는 진정한 '<em>즐기는 자</em>'다.</p>

<p>'스코빌 지수'란 고추류가 가진 매운맛의 원인인 캡사이신의 농도를 수치화 한 단위이다. 주헌이가 느끼는 매운 정도는 굉장히 독특한데, 먹고 있는 메뉴의 절대 수치가 아닌 음식과의 상대수치에 기반한다. 예를 들어 [5, 2, 8]의 스코빌 지수를 가진 음식을 먹을 때 주헌이가 느끼는 매운 정도는 가장 높은 수치인 8과 가장 낮은 수치인 2의 차이인 6만큼의 매운맛을 느낀다. 이처럼 메뉴들의 스코빌 지수가 있을 때 그 최댓값과 최솟값의 차이를 "주헌고통지수"라고 정의한다.</p>

<p style="text-align: center;"><img alt="" src="https://onlinejudgeimages.s3-ap-northeast-1.amazonaws.com/problem/15824/1.png" style="width: 224px; height: 118px;"></p>

<p style="text-align: center;">그림1. 고추처럼 보이지만 문제와는 무관합니다. </p>

<p>최근 주헌이에게 좋아하는 매운맛 전문점이 생겼다. 메뉴가 아주 다양한 이 음식점은 모든 메뉴의 스코빌 지수를 명시한 메뉴판을 제공한다. 주헌이의 목표는 이 음식점의 모든 음식 조합을 먹어보는 것이다. 하지만 주헌이는 까다로워서 한 번 먹어본 조합은 다시 먹지 않는다.</p>

<p>이 음식점의 모든 조합을 먹어 볼 때 주헌이가 즐길 수 있는 주헌고통지수의 합을 구해보자.</p>

### 입력 

 <p>첫 줄에 메뉴의 총 개수 N이 주어진다. 두 번째 줄에는 N개의 메뉴의 스코빌 지수가 주어진다. 모든 스코빌 지수는 0보다 크거나 같고 2<sup>31</sup>-1보다 작거나 같은 정수이다.</p>

### 출력 

 <p>한 줄에 모든 조합의 주헌고통지수 합을 1,000,000,007로 나눈 나머지를 출력한다.</p>


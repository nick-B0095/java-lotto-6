# 프로젝트 설명

우테코 프리코스 3주차 과제로 로또 판매와 게임 진행을 구현했습니다.
<br><br>
아래는 로또 판매 방식에 대한 설명입니다.<br>
로또 1장의 가격은 1000원으로 플레이어가 입력한 구입 금액 만큼 로또를 발행해야 합니다.<br>
당첨 번호와 보너스 번호를 입력받습니다.<br>
당첨 내역 및 수익률을 출력하고 게임을 종료합니다.<br>
<br>
아래는 로또 게임 진행 방식에 대한 설명 입니다.<br>
플레이어 로또 : 1~45 사이의 번호 6개를 중복되지 않도록 뽑습니다. 또한, 보너스 번호를 1개 뽑습니다.<br>
진행자(컴퓨터) 로또 : 당첨 번호 추첨을 합니다. 중복되지 않도록 로또 번호 6개를 뽑고 보너스 번호 1개를 뽑습니다.<br>
등수 : 1등 -> 6개 번호 일치<br>
2등 -> 5개 번호 일치 + 보너스 번호 일치<br>
3등 -> 5개 번호 일치<br>
4등 -> 4개 번호 일치<br>
5등 -> 3개 번호 일치

# Application 기능

- 로또 구입 금액입력 받기
- 당첨 번호 입력 받기
- 보너스 번호 입력 받기
- 로또 구매 개수 출력하기 및 번호 오름차순 정렬 후 출력하기
- 로또 게임 실행 (로또 구매 개수 만큼)
- 당첨 내역 출력하기 및 총 수익률 출력하기

# Lotto 클래스 기능

- 진행자 로또 번호 뽑기 (6개 + 1개)
- 번호 비교하기

# 프로그래머스 [위장](https://programmers.co.kr/learn/courses/30/lessons/42578)

## 1. 이해

- 적어도 한 개의 옷은 입는다.
- 같은 이름의 의상은 존재하지 않는다.
- 의상의 종류를 모두 포함하는 위장을 할 필요는 없다.
- 각 행은 [의상의 이름, 의상의 종류]

## 2. 계획

1. 의상 종류별 개수를 수집한다.
2. (의상 종류별 개수 + 1(선택 안 하는 경우의 수)) * 의상 종류수 - 1
3. 아무 것도 안 입는 경우는 없으므로 -1 해준다.

## 3. 실행

## 4. 반성

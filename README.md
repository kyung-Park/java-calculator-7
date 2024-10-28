# java-calculator-precourse

# 문자열 덧셈 계산기

## 요구 사항
1. 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.
2. 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다. 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
3. 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

## 기능 구현 목록
1. 기본 구분자로 쉼표(,)와 콜론(:)을 지원하는 기능 구현
2. 빈 문자열 또는 숫자 하나가 들어왔을 때 처리 기능 구현
3. 커스텀 구분자를 지원하는 기능 구현
4. 잘못된 값이 입력된 경우 예외 처리 구현
5. 음수가 포함된 경우 예외 처리 구현

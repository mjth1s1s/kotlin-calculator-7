# kotlin-calculator-precourse

1. 계산과 관련된 모든 기능을 담은 클래스 (Calculator 클래스)
2. 문자열을 입력받아 기본 구분자 혹은 커스텀 구분자에 따라 숫자 추출하여 리스트에 저장 (parseInput 메서드)
3. 기본 구분자인 경우 ,와 : 를 기준으로 숫자 분리해 리스트 반환 (defaultDel 메서드)
4. 커스텀 구분자인 경우 \n 을 기준으로 문자열을 나눈 뒷 부분을 구분자 기준으로 숫자 분리해 리스트 반환 (customDel 메서드)
5. 커스텀 구분자인 경우 문자열이 \n 을 기준으로 정상적으로 두 파트로 나눠지지 않을 경우 예외 발생 (customDel 메서드 개선)
6. 숫자 리스트의 각 숫자에 대해 정수로 변환할 수 없거나 음수일 경우 예외 발생 (runException 메서드)
7. 숫자 리스트의 합을 반환 (totalSum 메서드)
8. 빈문자열이나 null값일 경우 0 출력, 클래스와 함수들 호출 (main 함수)


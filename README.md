user_input = input("숫자를 입력하세요: ")

try:
    # 입력된 값을 정수로 변환합니다.
    number = int(user_input)
    
    # 짝수와 홀수를 판별합니다.
    if number % 2 == 0:
        print(f"{number}은(는) 짝수입니다.")
    else:
        print(f"{number}은(는) 홀수입니다.")
except ValueError:
    # 입력이 정수가 아닐 경우 오류 메시지를 출력합니다.
    print("유효한 숫자를 입력하세요.")

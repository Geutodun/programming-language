def x():       #함수 설정
    print("레이저")


x()            #함수 


def deposit(M, N):    #숫자 더하기
    print("입금이 완료되었습니다. 잔액은 {0} 원입니다".format(M + N))
    return M + N


def withdraw(M, N):    #숫자 뺴기
    if M >= N:  #남은게 잔액보다 많으면
        print("출금이 완료되었습니다. 잔액은 {0} 원 남았습니다".format(M - N))
        return M - N
    else:
        print("잔액이 부족합니다")
        return M



def withdraw_night(M, N):
    S = 600 #수수료
    return S, M - N - S





M = 5000
M = deposit(M, 2000)
M = withdraw(M, 500)
S, M = withdraw_night(M, 1000)
print("수수료는 {0} 원이며, 잔액은 {1} 원입니다.".format(S, M))
